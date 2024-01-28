---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1964).jpg]]"
---
[Time:: 2:04]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wooden Heart]]
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
		intensity: page["Wooden_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
