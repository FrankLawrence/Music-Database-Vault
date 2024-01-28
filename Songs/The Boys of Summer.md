---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Building the Perfect Beast (1984).jpg]]"
---
[Time:: 4:40]
[Artist:: [[Don Henley]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Building the Perfect Beast (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Boys of Summer]]
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
		intensity: page["The_Boys_of_Summer"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
