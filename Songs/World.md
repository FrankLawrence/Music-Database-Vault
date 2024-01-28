---
tags: Song ⭐⭐⭐ 
banner: "![[Horizontal (1968).jpg]]"
---
[Time:: 3:15]
[Artist:: [[Bee Gees]] ]
[Genre:: Psychedelic Pop]
[Played:: ]
[Album:: [[Horizontal (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[World]]
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
		intensity: page["World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
