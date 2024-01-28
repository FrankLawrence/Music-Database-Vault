---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Discovery (1990).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 11]
[Album:: [[Discovery (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Confusion]]
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
		intensity: page["Confusion"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
