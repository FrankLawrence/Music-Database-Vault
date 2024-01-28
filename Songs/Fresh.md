---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Emergency (1984).jpg]]"
---
[Time:: 3:50]
[Artist:: [[Kool & The Gang]] ]
[Genre:: Funk]
[Played:: 59]
[Album:: [[Emergency (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fresh]]
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
		intensity: page["Fresh"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
