---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Old Is New (2018).jpg]]"
---
[Time:: 4:31]
[Artist:: [[Toto]] ]
[Genre:: Pop Rock]
[Played:: 95]
[Album:: [[Old Is New (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Alone]]
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
		intensity: page["Alone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
