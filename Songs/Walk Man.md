---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:04]
[Artist:: [[Tiny Meat Gang]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 2]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Walk Man]]
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
		intensity: page["Walk_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
