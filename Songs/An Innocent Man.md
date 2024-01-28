---
tags: Song  
banner: "![[Piano Man (1983).jpg]]"
---
[Time:: 5:18]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Piano Man (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[An Innocent Man]]
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
		intensity: page["An_Innocent_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
