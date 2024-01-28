---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Toto IV (1982).jpg]]"
---
[Time:: 5:31]
[Artist:: [[Toto]] ]
[Genre:: Soft Rock]
[Played:: 5]
[Album:: [[Toto IV (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rosanna]]
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
		intensity: page["Rosanna"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
