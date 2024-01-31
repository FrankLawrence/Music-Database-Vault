---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: 
---
[Time:: 3:24]
[Artist:: [[Travis Scott]] [[Young Thug & M.I.A.]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 23]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[FRANCHISE]]
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
		intensity: page["FRANCHISE"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
