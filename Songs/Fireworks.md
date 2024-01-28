---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Crash! Boom! Bang! (1994).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Roxette]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Crash! Boom! Bang! (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fireworks]]
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
		intensity: page["Fireworks"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
