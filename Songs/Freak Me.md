---
tags: Song  

[Time:: 4:05]
[Artist:: [[Another Level]] ]
[Genre:: ]
[Played:: 11]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Freak Me]]
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
		intensity: page["Freak_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
