---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 5:35]
[Artist:: [[Jreg]] ]
[Genre:: ]
[Played:: 13]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[political compass rap]]
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
		intensity: page["political_compass_rap"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
