---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Led Zeppelin IV (1971).jpg]]"
---
[Time:: 8:02]
[Artist:: [[Led Zeppelin]] ]
[Genre:: Progressive Rock]
[Played:: ]
[Album:: [[Led Zeppelin IV (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stairway to Heaven]]
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
		intensity: page["Stairway_to_Heaven"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
