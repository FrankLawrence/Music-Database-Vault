---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Old Is New (2018).jpg]]"
---
[Time:: 4:24]
[Artist:: [[Toto]] ]
[Genre:: Pop Rock]
[Played:: 59]
[Album:: [[Old Is New (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Spanish Sea]]
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
		intensity: page["Spanish_Sea"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
