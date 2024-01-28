---
tags: Song ⭐⭐⭐ 
banner: "![[Breakfast In America (1979).jpg]]"
---
[Time:: 5:10]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Breakfast In America (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Take The Long Way Home]]
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
		intensity: page["Take_The_Long_Way_Home"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
