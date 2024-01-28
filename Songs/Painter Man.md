---
tags: Song ⭐⭐⭐ 
banner: "![[Gold - 20 Super Hits (1993).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Boney M.]] ]
[Genre:: Electronic]
[Played:: ]
[Album:: [[Gold - 20 Super Hits (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Painter Man]]
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
		intensity: page["Painter_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
