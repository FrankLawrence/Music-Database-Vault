---
tags: Song ⭐⭐⭐ 

[Time:: 3:24]
[Artist:: [[Neil Diamond]] ]
[Genre:: Soft Rock]
[Played:: ]
[Album:: ]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sweet Caroline]]
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
		intensity: page["Sweet_Caroline"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
