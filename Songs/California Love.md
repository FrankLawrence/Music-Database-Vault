---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[All Eyez on Me (1995).jpg]]"
---
[Time:: 4:45]
[Artist:: [[2Pac]] [[Dre. Dre and Roger Troutman]] ]
[Genre:: West Coast hip hop]
[Played:: 40]
[Album:: [[All Eyez on Me (1995)]]]
[Year:: 1995]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[California Love]]
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
		intensity: page["California_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
