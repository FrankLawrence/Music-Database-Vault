---
tags: Song  
banner: "![[Highway To Hell (1979).jpg]]"
---
[Time:: 4:17]
[Artist:: [[AC/DC]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Highway To Hell (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Hungry Man]]
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
		intensity: page["Love_Hungry_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
