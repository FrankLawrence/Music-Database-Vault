---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Gold - 20 Super Hits (1993).jpg]]"
---
[Time:: 3:57]
[Artist:: [[Boney M.]] ]
[Genre:: Electronic]
[Played:: 6]
[Album:: [[Gold - 20 Super Hits (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sunny]]
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
		intensity: page["Sunny"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
