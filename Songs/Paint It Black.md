---
tags: Song  
banner: "![[Aftermath (2007).jpg]]"
---
[Time:: 3:24]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Aftermath (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Paint It Black]]
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
		intensity: page["Paint_It_Black"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
