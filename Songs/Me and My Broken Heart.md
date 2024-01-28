---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Let the Road (2014).jpg]]"
---
[Time:: 3:15]
[Artist:: [[Rixton]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Let the Road (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Me and My Broken Heart]]
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
		intensity: page["Me_and_My_Broken_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
