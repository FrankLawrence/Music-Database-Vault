---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Music to Be Murderd By (2020).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Eminem]] [[Juice WRLD]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 14]
[Album:: [[Music to Be Murderd By (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Godzilla]]
````

  ```dataviewjs
const calendarData = { 
	colors: { 
		blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"] 
	}, 
	entries: [] 
}; 

for (let page of dv.pages('"Daily Notes"')) { 
	calendarData.entries.push({ 
		date: page.file.name, 
		intensity: page["Godzilla"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
