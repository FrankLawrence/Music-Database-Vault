---
tags: Song  
banner: "![[The Very Best Of Sandra [Disc 2] (2016).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Sandra]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Very Best Of Sandra [Disc 2] (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Forever]]
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
		intensity: page["Forever"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
