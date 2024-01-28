---
tags: Song ⭐ 💔

[Time:: 4:28]
[Artist:: [[SIDO]] [[Andreas Bourani]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Astronaut]]
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
		intensity: page["Astronaut"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
