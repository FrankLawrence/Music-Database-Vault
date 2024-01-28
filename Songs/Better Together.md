---
tags: Song ⭐⭐⭐ 
banner: "![[In Between Dreams (2005).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Jack Johnson]] ]
[Genre:: Acoutic rock]
[Played:: 2]
[Album:: [[In Between Dreams (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Better Together]]
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
		intensity: page["Better_Together"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
