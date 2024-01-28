---
tags: Song ⭐⭐ 
banner: "![[Humanz (2017).jpg]]"
---
[Time:: 6:13]
[Artist:: [[Gorillaz]] [[Popcaan]] ]
[Genre:: Dancehall]
[Played:: 2]
[Album:: [[Humanz (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Saturnz Barz]]
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
		intensity: page["Saturnz_Barz"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
