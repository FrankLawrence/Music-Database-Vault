---
tags: Song ⭐⭐⭐⭐⭐ 
banner: 
---
[Time:: 3:36]
[Artist:: [[JVKE]] ]
[Genre:: ]
[Played:: 61]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Golden hour]]
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
		intensity: page["Golden_hour"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
