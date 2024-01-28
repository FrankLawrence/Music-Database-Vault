---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Waterloo (1974).jpg]]"
---
[Time:: 2:43]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Waterloo (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Waterloo]]
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
		intensity: page["Waterloo"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
