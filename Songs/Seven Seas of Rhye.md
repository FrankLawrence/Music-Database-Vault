---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Queen II (1974).jpg]]"
---
[Time:: 2:49]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Queen II (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Seven Seas of Rhye]]
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
		intensity: page["Seven_Seas_of_Rhye"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
