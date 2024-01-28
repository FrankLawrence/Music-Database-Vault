---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[A New World Record (1976).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 8]
[Album:: [[A New World Record (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Livin' Thing]]
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
		intensity: page["Livin'_Thing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
