---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Balance of Power (1986).jpg]]"
---
[Time:: 4:30]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 19]
[Album:: [[Balance of Power (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Getting To The Point]]
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
		intensity: page["Getting_To_The_Point"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
