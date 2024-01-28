---
tags: Song ⭐⭐⭐ 
banner: "![[Naturally (1972).jpg]]"
---
[Time:: 3:25]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 1]
[Album:: [[Naturally (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Magnolia]]
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
		intensity: page["Magnolia"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
