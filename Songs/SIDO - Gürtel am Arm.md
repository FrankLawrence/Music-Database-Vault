---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:38]
[Artist:: [[SIDO]] ]
[Genre:: ]
[Played:: 4]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[SIDO - Gürtel am Arm]]
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
		intensity: page["SIDO_-_Gürtel_am_Arm"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
