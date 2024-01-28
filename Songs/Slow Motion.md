---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[New Age ().jpg]]"
---
[Time:: 3:49]
[Artist:: [[KSI & Randalf]] ]
[Genre:: ]
[Played:: 12]
[Album:: [[New Age ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Slow Motion]]
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
		intensity: page["Slow_Motion"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
