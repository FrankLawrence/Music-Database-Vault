---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Too-Rye-Ay (1982).jpg]]"
---
[Time:: 4:00]
[Artist:: [[Dexy's Midnight Runners and the Emerald Express]] ]
[Genre:: New Wave]
[Played:: 3]
[Album:: [[Too-Rye-Ay (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Come On Eileen]]
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
		intensity: page["Come_On_Eileen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
