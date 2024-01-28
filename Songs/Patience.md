---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 4:52]
[Artist:: [[Tame Impala]] ]
[Genre:: Psychedelic Pop]
[Played:: 32]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Patience]]
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
		intensity: page["Patience"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
