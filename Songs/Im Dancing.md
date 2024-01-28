---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[DJ Replay (2014).jpg]]"
---
[Time:: 2:09]
[Artist:: [[Max]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[DJ Replay (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Im Dancing]]
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
		intensity: page["Im_Dancing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
