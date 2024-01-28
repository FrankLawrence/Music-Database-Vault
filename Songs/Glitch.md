---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:05]
[Artist:: [[Martin Garrix]] [[Julian Jordan]] ]
[Genre:: Progressive House]
[Played:: 33]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Glitch]]
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
		intensity: page["Glitch"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
