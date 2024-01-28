---
tags: Song ⭐⭐⭐ 
banner: "![[Forever Young (1984).jpg]]"
---
[Time:: 3:38]
[Artist:: [[Alphaville]] ]
[Genre:: Synth-Pop]
[Played:: 1]
[Album:: [[Forever Young (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Forever Young]]
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
		intensity: page["Forever_Young"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
