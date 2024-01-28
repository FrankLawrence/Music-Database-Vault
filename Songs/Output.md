---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 2:42]
[Artist:: [[Max]] ]
[Genre:: ]
[Played:: 11]
[Played:: 2]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Output]]
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
		intensity: page["Output"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
