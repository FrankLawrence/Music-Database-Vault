---
tags: Song ⭐⭐⭐⭐⭐ 💛

[Time:: 2:58]
[Artist:: [[Rodrigo Amarante]] ]
[Genre:: ]
[Played:: 41]
[Played:: 6]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Silence]]
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
		intensity: page["Silence"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
