---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Gold - 20 Super Hits (1993).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Boney M.]] ]
[Genre:: Electronic]
[Played:: 8]
[Album:: [[Gold - 20 Super Hits (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Belfast]]
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
		intensity: page["Belfast"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
