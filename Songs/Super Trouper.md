---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Super Trouper (1980).jpg]]"
---
[Time:: 4:14]
[Artist:: [[ABBA]] ]
[Genre:: Electronic, Pop]
[Played:: 5]
[Album:: [[Super Trouper (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Super Trouper]]
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
		intensity: page["Super_Trouper"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
