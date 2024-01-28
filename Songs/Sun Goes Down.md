---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:15]
[Artist:: [[Fabian Mazur]] ]
[Genre:: Dance]
[Played:: 22]
[Played:: 1]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sun Goes Down]]
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
		intensity: page["Sun_Goes_Down"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
