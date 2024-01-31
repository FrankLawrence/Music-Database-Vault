---
tags: Song ⭐⭐⭐⭐ 
banner:
---
[Time:: 3:27]
[Artist:: [[ALLE FARBEN]] ]
[Genre:: Rock Pop]
[Played:: 1]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[SOMETIMES]]
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
		intensity: page["SOMETIMES"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
