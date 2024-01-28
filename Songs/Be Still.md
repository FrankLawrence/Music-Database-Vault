---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Battle Born (2012).jpg]]"
---
[Time:: 4:35]
[Artist:: [[The Killers]] ]
[Genre:: Synth-Pop]
[Played:: 39]
[Album:: [[Battle Born (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Be Still]]
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
		intensity: page["Be_Still"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
