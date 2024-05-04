---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Mirrors (1986).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Sandra]] ]
[Genre:: Electronic]
[Played:: 39]
[Album:: [[Mirrors (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Loreen]]
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
		intensity: page["Loreen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
