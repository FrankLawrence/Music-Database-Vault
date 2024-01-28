---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:23]
[Artist:: [[Alle Farben]] [[Graham Candy]] ]
[Genre:: Rock Pop]
[Played:: ]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[She Moves ]]
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
		intensity: page["She_Moves_"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
