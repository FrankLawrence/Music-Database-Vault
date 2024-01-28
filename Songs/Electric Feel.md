---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Oracluar Spectacular (2007).jpg]]"
---
[Time:: 3:50]
[Artist:: [[MGMT]] ]
[Genre:: Psychedelic Pop]
[Played:: 3]
[Album:: [[Oracluar Spectacular (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Electric Feel]]
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
		intensity: page["Electric_Feel"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
