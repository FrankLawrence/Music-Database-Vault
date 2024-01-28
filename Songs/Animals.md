---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[V (2014).jpg]]"
---
[Time:: 3:49]
[Artist:: [[Maroon 5]] ]
[Genre:: Dance-pop]
[Played:: 9]
[Album:: [[V (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Animals]]
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
		intensity: page["Animals"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
