---
tags: Song ⭐⭐⭐⭐ 

[Time:: 4:47]
[Artist:: [[Blue Mitchell]] ]
[Genre:: ]
[Played:: 8]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Daydream]]
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
		intensity: page["Daydream"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
