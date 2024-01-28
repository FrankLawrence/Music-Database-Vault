---
tags: Song  
banner: "![[Crime of the Century (1974).jpg]]"
---
[Time:: 4:05]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 1]
[Album:: [[Crime of the Century (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[If Everyone Was Listening]]
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
		intensity: page["If_Everyone_Was_Listening"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
