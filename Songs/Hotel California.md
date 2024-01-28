---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hotel California (1976).jpg]]"
---
[Time:: 6:30]
[Artist:: [[The Eagles]] ]
[Genre:: Rock]
[Played:: 19]
[Album:: [[Hotel California (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hotel California]]
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
		intensity: page["Hotel_California"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
