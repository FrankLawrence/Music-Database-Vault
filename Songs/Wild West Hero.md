---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Out of the Blue (1990).jpg]]"
---
[Time:: 4:42]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 6]
[Album:: [[Out of the Blue (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wild West Hero]]
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
		intensity: page["Wild_West_Hero"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
