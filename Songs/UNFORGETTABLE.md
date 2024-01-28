---
tags: Song ⭐⭐⭐ 

[Time:: 3:49]
[Artist:: [[Robin_Schulz]] ]
[Genre:: Rock Pop]
[Played:: ]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[UNFORGETTABLE]]
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
		intensity: page["UNFORGETTABLE"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
