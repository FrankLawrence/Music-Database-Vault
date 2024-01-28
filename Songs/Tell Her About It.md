---
tags: Song ⭐⭐⭐ 
banner: "![[Piano Man (1983).jpg]]"
---
[Time:: 3:52]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[Piano Man (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Tell Her About It]]
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
		intensity: page["Tell_Her_About_It"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
