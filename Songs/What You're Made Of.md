---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:08]
[Artist:: [[Arrested Youth]] ]
[Genre:: ]
[Played:: 23]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What You're Made Of]]
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
		intensity: page["What_You're_Made_Of"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
