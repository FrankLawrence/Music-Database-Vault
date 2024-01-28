---
tags: Song ⭐⭐⭐ 
banner: "![[Birds in the Trap Sing McKnight (2016).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Travis Scott]] [[Kendrick Lamar]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 4]
[Album:: [[Birds in the Trap Sing McKnight (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Goosebumps]]
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
		intensity: page["Goosebumps"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
