---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1977).jpg]]"
---
[Time:: 2:39]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Way Down]]
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
		intensity: page["Way_Down"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
