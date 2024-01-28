---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Super trouper (1980).jpg]]"
---
[Time:: 4:24]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[Super trouper (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Happy New Year]]
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
		intensity: page["Happy_New_Year"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
