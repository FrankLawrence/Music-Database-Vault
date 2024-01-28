---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Revenge ().jpg]]"
---
[Time:: 4:30]
[Artist:: [[Eurythmics]] ]
[Genre:: Pop Rock]
[Played:: ]
[Album:: [[Revenge ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[When Tomorrow Comes]]
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
		intensity: page["When_Tomorrow_Comes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
