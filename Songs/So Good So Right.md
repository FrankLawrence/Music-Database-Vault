---
tags: Song  
banner: "![[Jazz (1979).jpg]]"
---
[Time:: 3:20]
[Artist:: [[Brenda Russell]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[So Good So Right]]
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
		intensity: page["So_Good_So_Right"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
