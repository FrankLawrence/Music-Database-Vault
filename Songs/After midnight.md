---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Naturally (1972).jpg]]"
---
[Time:: 2:23]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 12]
[Album:: [[Naturally (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[After midnight]]
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
		intensity: page["After_midnight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
