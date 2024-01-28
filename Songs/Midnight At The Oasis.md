---
tags: Song  
banner: "![[Jazz (1999).jpg]]"
---
[Time:: 3:52]
[Artist:: [[Martin Taylor]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1999)]]]
[Year:: 1999]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Midnight At The Oasis]]
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
		intensity: page["Midnight_At_The_Oasis"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
