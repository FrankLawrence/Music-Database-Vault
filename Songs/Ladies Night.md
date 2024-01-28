---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Ladies' Night (1979).jpg]]"
---
[Time:: 6:26]
[Artist:: [[Kool & The Gang]] ]
[Genre:: Disco]
[Played:: 9]
[Album:: [[Ladies' Night (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ladies Night]]
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
		intensity: page["Ladies_Night"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
