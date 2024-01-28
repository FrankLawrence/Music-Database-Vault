---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Somebody's Watching Me (1984).jpg]]"
---
[Time:: 3:36]
[Artist:: [[Rockwell]] ]
[Genre:: Synth-Funk]
[Played:: 1]
[Album:: [[Somebody's Watching Me (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Somebody's Watching Me]]
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
		intensity: page["Somebody's_Watching_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
