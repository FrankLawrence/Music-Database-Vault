---
tags: Song  
banner: "![[News of the World (1977).jpg]]"
---
[Time:: 4:32]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[News of the World (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Spread Your Wings]]
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
		intensity: page["Spread_Your_Wings"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
