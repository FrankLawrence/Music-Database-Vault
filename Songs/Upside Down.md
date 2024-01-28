---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Diana (1980).jpg]]"
---
[Time:: 4:06]
[Artist:: [[Diana Ross]] ]
[Genre:: R&B]
[Played:: 6]
[Album:: [[Diana (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Upside Down]]
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
		intensity: page["Upside_Down"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
