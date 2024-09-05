---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Balance of Power (1990).jpg]]"
---
[Time:: 3:27]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 39]
[Album:: [[Balance of Power (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Calling America]]
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
		intensity: page["Calling_America"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
