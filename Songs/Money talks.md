---
tags: Song ⭐⭐⭐⭐ 
banner: "![[#8 (1983).jpg]]"
---
[Time:: 4:17]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 3]
[Album:: [[#8 (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Money talks]]
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
		intensity: page["Money_talks"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
