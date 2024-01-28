---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 4:17]
[Artist:: [[Foster the People]] ]
[Genre:: Alternative]
[Played:: 10]
[Played:: 1]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Imagination]]
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
		intensity: page["Imagination"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
