---
tags: Song ⭐⭐⭐⭐ 
banner:
---
[Time:: 3:41]
[Artist:: [[Frans]] ]
[Genre:: ]
[Played:: 1]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[If I Were Sorry]]
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
		intensity: page["If_I_Were_Sorry"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
