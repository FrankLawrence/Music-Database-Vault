---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Die 80er Show 2 CD1 (1983).jpg]]"
---
[Time:: 3:06]
[Artist:: [[Hubert Kah]] ]
[Genre:: Oldies]
[Played:: 6]
[Album:: [[Die 80er Show 2 CD1 (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sternenhimmel]]
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
		intensity: page["Sternenhimmel"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
