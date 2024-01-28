---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1960).jpg]]"
---
[Time:: 3:09]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1960)]]]
[Year:: 1960]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Are You Lonesome Tonight]]
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
		intensity: page["Are_You_Lonesome_Tonight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
