---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Communion (2015).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Years & Years]] ]
[Genre:: Synth-Pop]
[Played:: 29]
[Album:: [[Communion (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[King ]]
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
		intensity: page["King_"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
