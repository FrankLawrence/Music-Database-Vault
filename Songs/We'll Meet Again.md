---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:16]
[Artist:: [[TheFatRat & Laura Brehm]] ]
[Genre:: ]
[Played:: 7]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We'll Meet Again]]
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
		intensity: page["We'll_Meet_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
