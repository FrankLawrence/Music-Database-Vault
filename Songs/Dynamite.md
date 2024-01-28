---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Dynamite (2020).jpg]]"
---
[Time:: 3:19]
[Artist:: [[BTS]] ]
[Genre:: Disco-pop]
[Played:: 21]
[Album:: [[Dynamite (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dynamite]]
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
		intensity: page["Dynamite"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
