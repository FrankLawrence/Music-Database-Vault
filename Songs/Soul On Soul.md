---
tags: Song  
banner: "![[Jazz (1998).jpg]]"
---
[Time:: 5:14]
[Artist:: [[Rick Braun]] [[Maysa]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Jazz (1998)]]]
[Year:: 1998]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Soul On Soul]]
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
		intensity: page["Soul_On_Soul"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
