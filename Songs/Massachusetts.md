---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Horizontal (1968).jpg]]"
---
[Time:: 2:24]
[Artist:: [[Bee Gees]] ]
[Genre:: Psychedelic Pop]
[Played:: 1]
[Album:: [[Horizontal (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Massachusetts]]
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
		intensity: page["Massachusetts"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
