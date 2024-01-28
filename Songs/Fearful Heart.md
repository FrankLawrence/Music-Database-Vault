---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Old Is New (2018).jpg]]"
---
[Time:: 3:53]
[Artist:: [[Toto]] ]
[Genre:: Pop Rock]
[Played:: 25]
[Album:: [[Old Is New (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fearful Heart]]
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
		intensity: page["Fearful_Heart"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
