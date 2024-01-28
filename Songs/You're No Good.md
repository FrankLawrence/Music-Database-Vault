---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:44]
[Artist:: [[Linda Ronstadt]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You're No Good]]
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
		intensity: page["You're_No_Good"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
