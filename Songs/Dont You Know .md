---
tags: Song ⭐⭐⭐ 

[Time:: 3:20]
[Artist:: [[Kungs]] [[Jamie N Common]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dont You Know ]]
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
		intensity: page["Dont_You_Know_"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
