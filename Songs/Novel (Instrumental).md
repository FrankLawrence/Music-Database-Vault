---
tags: Song  

[Time:: 3:26]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Novel (Instrumental)]]
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
		intensity: page["Novel_(Instrumental)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
