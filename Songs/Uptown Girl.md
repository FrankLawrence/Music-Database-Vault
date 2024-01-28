---
tags: Song ⭐⭐⭐ 
banner: "![[Piano Man (1983).jpg]]"
---
[Time:: 3:18]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[Piano Man (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Uptown Girl]]
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
		intensity: page["Uptown_Girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
