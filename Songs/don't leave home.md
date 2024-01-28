---
tags: Song ⭐⭐⭐⭐ 
banner: "![[don't leave home (2003).jpg]]"
---
[Time:: 3:47]
[Artist:: [[Dido]] ]
[Genre:: Pop]
[Played:: 21]
[Album:: [[don't leave home (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[don't leave home]]
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
		intensity: page["don't_leave_home"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
