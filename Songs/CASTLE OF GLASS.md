---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Living Things (2012).jpg]]"
---
[Time:: 3:26]
[Artist:: [[Linkin Park]] ]
[Genre:: Electronic Rock]
[Played:: 8]
[Album:: [[Living Things (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[CASTLE OF GLASS]]
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
		intensity: page["CASTLE_OF_GLASS"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
