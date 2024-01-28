---
tags: Song ⭐⭐⭐ 

[Time:: 14:57]
[Artist:: [[Achim Reichel]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Boxer Kutte]]
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
		intensity: page["Boxer_Kutte"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
