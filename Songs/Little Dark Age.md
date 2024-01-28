---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Little Dark Age (2018).jpg]]"
---
[Time:: 5:00]
[Artist:: [[MGMT]] ]
[Genre:: Synth-Pop]
[Played:: 103]
[Album:: [[Little Dark Age (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Little Dark Age]]
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
		intensity: page["Little_Dark_Age"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
