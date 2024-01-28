---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Visage (1980).jpg]]"
---
[Time:: 8:35]
[Artist:: [[Visage]] ]
[Genre:: Synth-Pop]
[Played:: 14]
[Album:: [[Visage (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fade To Grey]]
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
		intensity: page["Fade_To_Grey"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
