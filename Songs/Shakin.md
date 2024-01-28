---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:08]
[Artist:: [[Eddie Money]] ]
[Genre:: ]
[Played:: 2]
[Album:: ]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shakin]]
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
		intensity: page["Shakin"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
