---
tags: Song ⭐⭐⭐ 
banner: "![[Price Tag (2011).jpg]]"
---
[Time:: 3:45]
[Artist:: [[Jessie J]] [[B.o.B.]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Price Tag (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Price Tag]]
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
		intensity: page["Price_Tag"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
