---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Stars (1991).jpg]]"
---
[Time:: 4:06]
[Artist:: [[Simply Red]] ]
[Genre:: Pop Rock]
[Played:: 39]
[Album:: [[Stars (1991)]]]
[Year:: 1991]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stars]]
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
		intensity: page["Stars"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
