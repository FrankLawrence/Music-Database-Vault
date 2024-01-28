---
tags: Song  
banner: "![[Jazz (1987).jpg]]"
---
[Time:: 4:38]
[Artist:: [[Gerald Albright]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Jazz (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[So Amazing]]
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
		intensity: page["So_Amazing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
