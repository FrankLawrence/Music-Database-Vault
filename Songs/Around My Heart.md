---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of Sandra [Disc 2] (2016).jpg]]"
---
[Time:: 3:16]
[Artist:: [[Sandra]] ]
[Genre:: Pop]
[Played:: 9]
[Album:: [[The Very Best Of Sandra [Disc 2] (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Around My Heart]]
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
		intensity: page["Around_My_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
