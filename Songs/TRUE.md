---
tags: Song  
banner: "![[TRUE (1983).jpg]]"
---
[Time:: 5:17]
[Artist:: [[Spandau Ballet]] ]
[Genre:: ]
[Played:: 3]
[Album:: [[TRUE (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[TRUE]]
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
		intensity: page["TRUE"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
