---
tags: Song ⭐⭐⭐⭐ 

[Time:: 4:08]
[Artist:: [[SIDO]] ]
[Genre:: ]
[Played:: 3]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sido - Sie bleibt]]
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
		intensity: page["Sido_-_Sie_bleibt"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
