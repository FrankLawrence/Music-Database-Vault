---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:57]
[Artist:: [[Martin Garrix & Dean Lewis]] ]
[Genre:: Dance]
[Played:: 38]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Used To Love]]
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
		intensity: page["Used_To_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
