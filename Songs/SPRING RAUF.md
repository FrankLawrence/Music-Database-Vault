---
tags: Song ⭐⭐⭐ 

[Time:: 3:14]
[Artist:: [[SIDO]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[SPRING RAUF]]
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
		intensity: page["SPRING_RAUF"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
