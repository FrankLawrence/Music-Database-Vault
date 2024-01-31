---
tags: Song ⭐⭐⭐⭐⭐ 
banner:
---
[Time:: 2:27]
[Artist:: [[Citylights]] ]
[Genre:: ]
[Played:: 2]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Feather]]
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
		intensity: page["Feather"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
