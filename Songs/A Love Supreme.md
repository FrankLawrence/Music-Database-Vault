---
tags: Song  
banner: "![[Jazz (1988).jpg]]"
---
[Time:: 3:37]
[Artist:: [[Will Downing]] ]
[Genre:: Jazz]
[Played:: ]
[Album:: [[Jazz (1988)]]]
[Year:: 1988]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Love Supreme]]
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
		intensity: page["A_Love_Supreme"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
