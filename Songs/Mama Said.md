---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:29]
[Artist:: [[Lukas Graham]] ]
[Genre:: Rock/Pop]
[Played:: 1]
[Album:: ]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Mama Said]]
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
		intensity: page["Mama_Said"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
