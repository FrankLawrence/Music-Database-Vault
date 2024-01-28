---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Their Greatest Hits (1973).jpg]]"
---
[Time:: 4:58]
[Artist:: [[Hot Chocolate]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Their Greatest Hits (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Brother Loui]]
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
		intensity: page["Brother_Loui"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
