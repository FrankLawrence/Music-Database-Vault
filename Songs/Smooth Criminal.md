---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Bad (1986).jpg]]"
---
[Time:: 4:20]
[Artist:: [[Michael Jackson]] ]
[Genre:: Pop Rock]
[Played:: 1]
[Album:: [[Bad (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Smooth Criminal]]
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
		intensity: page["Smooth_Criminal"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
