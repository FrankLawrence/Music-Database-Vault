---
tags: Song ⭐⭐⭐ 

[Time:: 3:34]
[Artist:: [[Lily Allen]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hard Out Here]]
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
		intensity: page["Hard_Out_Here"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
