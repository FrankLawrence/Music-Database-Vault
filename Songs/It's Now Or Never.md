---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1960).jpg]]"
---
[Time:: 3:18]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1960)]]]
[Year:: 1960]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[It's Now Or Never]]
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
		intensity: page["It's_Now_Or_Never"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
