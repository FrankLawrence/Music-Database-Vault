---
tags: Song ⭐⭐⭐ 
banner: "![[Willy and the Poor Boys (1969).jpg]]"
---
[Time:: 2:17]
[Artist:: [[Creedence Clearwater Revival]] ]
[Genre:: Hard Rock]
[Played:: 2]
[Album:: [[Willy and the Poor Boys (1969)]]]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fortunate Son]]
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
		intensity: page["Fortunate_Son"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
