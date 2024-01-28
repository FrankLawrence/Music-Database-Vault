---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1969).jpg]]"
---
[Time:: 3:05]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1969)]]]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[In The Ghetto]]
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
		intensity: page["In_The_Ghetto"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
