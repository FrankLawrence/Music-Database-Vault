---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 2:49]
[Artist:: [[Jagwar Twin]] ]
[Genre:: Alternative Rock]
[Played:: 10]
[Album:: ]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Happy Face]]
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
		intensity: page["Happy_Face"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
