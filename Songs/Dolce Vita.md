---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner:
---
[Time:: 3:55]
[Artist:: [[Ryan Paris]] ]
[Genre:: Italo Disco]
[Played:: 16]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dolce Vita]]
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
		intensity: page["Dolce_Vita"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
