---
tags: Song  
banner: "![[Highway To Hell (1979).jpg]]"
---
[Time:: 6:16]
[Artist:: [[AC/DC]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Highway To Hell (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Night Prowler]]
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
		intensity: page["Night_Prowler"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
