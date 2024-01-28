---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1961).jpg]]"
---
[Time:: 1:55]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1961)]]]
[Year:: 1961]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Surrender]]
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
		intensity: page["Surrender"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
