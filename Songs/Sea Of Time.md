---
tags: Song  
banner: "![[Yellow Submarine ().jpg]]"
---
[Time:: 3:00]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[Yellow Submarine ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sea Of Time]]
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
		intensity: page["Sea_Of_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
