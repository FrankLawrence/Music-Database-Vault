---
tags: Song ⭐⭐⭐⭐ 
banner: "![[1000 Forms of Fear (2014).jpg]]"
---
[Time:: 3:36]
[Artist:: [[Sia]] ]
[Genre:: Electropop]
[Played:: 2]
[Album:: [[1000 Forms of Fear (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Chandelier]]
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
		intensity: page["Chandelier"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
