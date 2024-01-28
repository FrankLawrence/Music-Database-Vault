---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 4:01]
[Artist:: [[SIDO]] ]
[Genre:: ]
[Played:: 26]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Löwenzahn]]
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
		intensity: page["Löwenzahn"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
