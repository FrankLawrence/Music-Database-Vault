---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:04]
[Artist:: [[Julian Calor]] ]
[Genre:: ]
[Played:: 25]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Liberation]]
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
		intensity: page["Liberation"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
