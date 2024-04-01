---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Hits (1983).jpg]]"
---
[Time:: 3:49]
[Artist:: [[Eurythmics]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Greatest Hits (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[who's that girl]]
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
		intensity: page["who's_that_girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
