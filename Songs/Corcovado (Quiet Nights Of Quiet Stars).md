---
tags: Song  
banner: "![[Jazz (1962).jpg]]"
---
[Time:: 2:59]
[Artist:: [[Stan Getz]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1962)]]]
[Year:: 1962]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Corcovado (Quiet Nights Of Quiet Stars)]]
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
		intensity: page["Corcovado_(Quiet_Nights_Of_Quiet_Stars)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
