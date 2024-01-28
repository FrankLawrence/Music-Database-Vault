---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:45]
[Artist:: [[Riggi & Piros vs. ZAXX]] ]
[Genre::  ]
[Played:: 3]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[ALPHA]]
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
		intensity: page["ALPHA"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
