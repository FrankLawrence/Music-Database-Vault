---
tags: Song ⭐⭐⭐ 
banner: "![[No Sound Without Silence (2014).jpg]]"
---
[Time:: 4:04]
[Artist:: [[The Script]] ]
[Genre:: Pop Rock]
[Played:: 1]
[Album:: [[No Sound Without Silence (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Superheroes]]
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
		intensity: page["Superheroes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
