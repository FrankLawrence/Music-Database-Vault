---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Supermodel (2014).jpg]]"
---
[Time:: 4:49]
[Artist:: [[Foster the People]] ]
[Genre:: Indie pop]
[Played:: 4]
[Album:: [[Supermodel (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Coming of Age]]
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
		intensity: page["Coming_of_Age"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
