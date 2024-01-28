---
tags: Song ⭐⭐ 
banner: "![[Humanz (2017).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Gorillaz]] [[D.R.A.M.]] ]
[Genre:: Electropop]
[Played:: 1]
[Album:: [[Humanz (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Andromeda]]
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
		intensity: page["Andromeda"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
