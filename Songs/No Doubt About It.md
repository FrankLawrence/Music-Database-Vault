---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Their Greatest Hits (1980).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Hot Chocolate]] ]
[Genre:: Pop]
[Played:: 81]
[Album:: [[Their Greatest Hits (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[No Doubt About It]]
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
		intensity: page["No_Doubt_About_It"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
