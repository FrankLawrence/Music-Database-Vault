---
tags: Song ⭐⭐⭐⭐ 
banner: "![[St. Louis to Liverpool (1964).jpg]]"
---
[Time:: 2:41]
[Artist:: [[Chuck Berry]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[St. Louis to Liverpool (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Never Can Tell]]
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
		intensity: page["You_Never_Can_Tell"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
