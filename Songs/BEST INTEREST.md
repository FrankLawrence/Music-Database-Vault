---
tags: Song ⭐⭐⭐⭐⭐ 
banner: 
---
[Time:: 2:14]
[Artist:: [[Tyler, the Creator]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 33]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[BEST INTEREST]]
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
		intensity: page["BEST_INTEREST"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
