---
tags: Song ⭐⭐⭐⭐ 
banner: "![[So Good (2015).jpg]]"
---
[Time:: 3:21]
[Artist:: [[Zara Larsson]] ]
[Genre:: Electropop]
[Played:: 1]
[Album:: [[So Good (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lush Life]]
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
		intensity: page["Lush_Life"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
