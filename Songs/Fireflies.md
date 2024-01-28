---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Ocean Eyes (2009).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Owl City]] ]
[Genre:: Synth-Pop]
[Played:: 24]
[Album:: [[Ocean Eyes (2009)]]]
[Year:: 2009]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fireflies]]
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
		intensity: page["Fireflies"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
