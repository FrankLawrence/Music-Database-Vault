---
tags: Song  
banner: "![[Jazz (2000).jpg]]"
---
[Time:: 3:21]
[Artist:: [[Jeff Golub]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Drop Top]]
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
		intensity: page["Drop_Top"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
