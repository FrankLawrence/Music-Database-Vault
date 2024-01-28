---
tags: Song ⭐⭐⭐⭐ 

[Time:: 2:38]
[Artist:: [[XXXTENTACION]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 3]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[whoa (mind in awe)]]
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
		intensity: page["whoa_(mind_in_awe)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
