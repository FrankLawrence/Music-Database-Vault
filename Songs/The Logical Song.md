---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Breakfast In America (1979).jpg]]"
---
[Time:: 4:11]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 24]
[Album:: [[Breakfast In America (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Logical Song]]
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
		intensity: page["The_Logical_Song"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
