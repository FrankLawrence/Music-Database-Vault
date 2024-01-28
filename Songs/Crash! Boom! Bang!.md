---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Crash! Boom! Bang! (1994).jpg]]"
---
[Time:: 5:02]
[Artist:: [[Roxette]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Crash! Boom! Bang! (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Crash! Boom! Bang!]]
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
		intensity: page["Crash!_Boom!_Bang!"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
