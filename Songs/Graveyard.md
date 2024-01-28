---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Manic (2020).jpg]]"
---
[Time:: 3:03]
[Artist:: [[Halsey]] ]
[Genre:: Electropop]
[Played:: 16]
[Album:: [[Manic (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Graveyard]]
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
		intensity: page["Graveyard"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
