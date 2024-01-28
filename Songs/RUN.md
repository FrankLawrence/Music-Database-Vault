---
tags: Song ⭐⭐⭐ 

[Time:: 4:01]
[Artist:: [[AWOLNATION]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[RUN]]
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
		intensity: page["RUN"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
