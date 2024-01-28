---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Celebrate! (1980).jpg]]"
---
[Time:: 3:41]
[Artist:: [[Kool & The Gang]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[Celebrate! (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Celebration]]
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
		intensity: page["Celebration"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
