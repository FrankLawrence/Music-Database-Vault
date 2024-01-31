---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner:
---
[Time:: 2:16]
[Artist:: [[Dick Dale]] ]
[Genre:: Instrumental Rock]
[Played:: 17]
[Year:: 1962]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Misirlou]]
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
		intensity: page["Misirlou"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
