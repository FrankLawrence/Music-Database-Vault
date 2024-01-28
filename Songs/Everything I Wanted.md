---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 4:06]
[Artist:: [[Billie Eilish]] ]
[Genre:: Alternative]
[Played:: 22]
[Played:: 2]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everything I Wanted]]
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
		intensity: page["Everything_I_Wanted"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
