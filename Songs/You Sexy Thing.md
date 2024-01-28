---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Their Greatest Hits (1975).jpg]]"
---
[Time:: 4:05]
[Artist:: [[Hot Chocolate]] ]
[Genre:: Pop]
[Played:: 11]
[Album:: [[Their Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Sexy Thing]]
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
		intensity: page["You_Sexy_Thing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
