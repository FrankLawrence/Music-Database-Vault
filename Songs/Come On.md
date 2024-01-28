---
tags: Song  
banner: "![[The Very Best of the Rolling Stones (2007).jpg]]"
---
[Time:: 1:50]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[The Very Best of the Rolling Stones (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Come On]]
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
		intensity: page["Come_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
