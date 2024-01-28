---
tags: Song  
banner: "![[The Beatles (White Album) [Disc 2] (1968).jpg]]"
---
[Time:: 8:22]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[The Beatles (White Album) [Disc 2] (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Revolution 9]]
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
		intensity: page["Revolution_9"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
