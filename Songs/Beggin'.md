---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[So Dark the Con of Man (2017).jpg]]"
---
[Time:: 3:36]
[Artist:: [[Madcon]] ]
[Genre:: Hip-Hop]
[Played:: 21]
[Album:: [[So Dark the Con of Man (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Beggin']]
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
		intensity: page["Beggin'"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
