---
tags: Song ⭐⭐⭐⭐ 
banner:
---
[Time:: 3:51]
[Artist:: [[Welshly Arms]] ]
[Genre:: ]
[Played:: 5]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Legendary]]
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
		intensity: page["Legendary"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
