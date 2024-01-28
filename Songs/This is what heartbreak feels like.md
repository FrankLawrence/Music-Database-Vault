---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 2:36]
[Artist:: [[JVKE]] ]
[Genre:: ]
[Played:: 13]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This is what heartbreak feels like]]
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
		intensity: page["This_is_what_heartbreak_feels_like"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
