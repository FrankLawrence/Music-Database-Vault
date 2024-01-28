---
tags: Song ⭐⭐⭐ 

[Time:: 6:17]
[Artist:: [[Joachim Witt]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Kosmetik]]
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
		intensity: page["Kosmetik"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
