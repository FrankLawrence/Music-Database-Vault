---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Their Greatest Hits (1977).jpg]]"
---
[Time:: 4:29]
[Artist:: [[Hot Chocolate]] ]
[Genre:: Pop]
[Played:: 14]
[Album:: [[Their Greatest Hits (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[So You Win Again]]
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
		intensity: page["So_You_Win_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
