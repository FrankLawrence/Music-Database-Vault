---
tags: Song  
banner: "![[Yellow Submarine ().jpg]]"
---
[Time:: 2:21]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Yellow Submarine ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Pepperland]]
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
		intensity: page["Pepperland"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
