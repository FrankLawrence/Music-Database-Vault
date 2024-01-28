---
tags: Song ⭐⭐⭐⭐ 

[Time:: 2:52]
[Artist:: [[Billy Ocean]] ]
[Genre:: Pop]
[Played:: 1]
[Played:: 1]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love really hurts without you]]
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
		intensity: page["Love_really_hurts_without_you"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
