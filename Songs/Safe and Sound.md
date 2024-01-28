---
tags: Song ⭐⭐⭐⭐ 
banner: "![[In a Tidal Wave of Mystery (2011).jpg]]"
---
[Time:: 3:11]
[Artist:: [[Capital Cities]] ]
[Genre:: Synth-Pop]
[Played:: 2]
[Album:: [[In a Tidal Wave of Mystery (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Safe and Sound]]
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
		intensity: page["Safe_and_Sound"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
