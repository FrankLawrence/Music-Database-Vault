---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Face the Music (1976).jpg]]"
---
[Time:: 4:08]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 9]
[Album:: [[Face the Music (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Strange Magic]]
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
		intensity: page["Strange_Magic"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
