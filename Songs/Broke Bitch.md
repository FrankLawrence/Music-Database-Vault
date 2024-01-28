---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 2:27]
[Artist:: [[Tiny Meat Gang]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 13]
[Album:: ]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Broke Bitch]]
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
		intensity: page["Broke_Bitch"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
