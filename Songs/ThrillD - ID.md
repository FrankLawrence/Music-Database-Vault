---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:39]
[Artist:: [[Max]] ]
[Genre:: Dance]
[Played:: 1]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[ThrillD - ID]]
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
		intensity: page["ThrillD_-_ID"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
