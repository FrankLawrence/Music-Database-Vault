---
tags: Song ⭐⭐⭐⭐ 
banner: "![[BASF Jazz side A ().jpg]]"
---
[Time:: 47:20]
[Artist:: [[Jazz]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[BASF Jazz side A ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jazz]]
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
		intensity: page["Jazz"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
