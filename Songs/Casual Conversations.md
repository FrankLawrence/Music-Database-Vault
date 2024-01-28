---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Breakfast In America (1979).jpg]]"
---
[Time:: 2:59]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 13]
[Album:: [[Breakfast In America (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Casual Conversations]]
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
		intensity: page["Casual_Conversations"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
