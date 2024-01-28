---
tags: Song ⭐⭐ 

[Time:: 4:24]
[Artist:: [[Seiler und Speer]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ham kummst]]
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
		intensity: page["Ham_kummst"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
