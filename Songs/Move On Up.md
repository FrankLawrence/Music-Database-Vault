---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Jazz (1971).jpg]]"
---
[Time:: 3:23]
[Artist:: [[Curtis Mayfield]] ]
[Genre:: Jazz]
[Played:: 8]
[Album:: [[Jazz (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Move On Up]]
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
		intensity: page["Move_On_Up"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
