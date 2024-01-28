---
tags: Song ⭐⭐⭐⭐ 

[Time:: 4:59]
[Artist:: [[M35 Wasback Elle Vee]] ]
[Genre:: ]
[Played:: 5]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let It Go]]
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
		intensity: page["Let_It_Go"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
