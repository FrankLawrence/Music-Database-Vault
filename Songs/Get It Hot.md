---
tags: Song  
banner: "![[Highway To Hell (1979).jpg]]"
---
[Time:: 2:34]
[Artist:: [[AC/DC]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Highway To Hell (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Get It Hot]]
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
		intensity: page["Get_It_Hot"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
