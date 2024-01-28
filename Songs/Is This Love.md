---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Whitesnake (1988).jpg]]"
---
[Time:: 4:44]
[Artist:: [[Whitesnake]] ]
[Genre:: Metal]
[Played:: 5]
[Album:: [[Whitesnake (1988)]]]
[Year:: 1988]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Is This Love]]
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
		intensity: page["Is_This_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
