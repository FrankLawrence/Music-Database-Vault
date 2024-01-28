---
tags: Song  
banner: "![[The Very Best Of Sandra [Disc 2] (2016).jpg]]"
---
[Time:: 4:02]
[Artist:: [[Sandra]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Very Best Of Sandra [Disc 2] (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heaven Can Wait]]
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
		intensity: page["Heaven_Can_Wait"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
