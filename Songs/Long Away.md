---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Day at the Races (1976).jpg]]"
---
[Time:: 3:34]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: ]
[Album:: [[A Day at the Races (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Long Away]]
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
		intensity: page["Long_Away"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
