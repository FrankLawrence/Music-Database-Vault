---
tags: Song ⭐⭐⭐⭐ 

[Time:: 4:12]
[Artist:: [[Birdy]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[People Help The People]]
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
		intensity: page["People_Help_The_People"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
