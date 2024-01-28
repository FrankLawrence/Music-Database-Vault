---
tags: Song ⭐⭐⭐ 
banner: "![[Fragile (1971).jpg]]"
---
[Time:: 8:36]
[Artist:: [[Yes]] ]
[Genre:: Progressive Rock]
[Played:: ]
[Album:: [[Fragile (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Roundabout]]
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
		intensity: page["Roundabout"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
