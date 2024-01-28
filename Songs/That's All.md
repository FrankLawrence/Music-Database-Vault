---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Genesis (1983).jpg]]"
---
[Time:: 4:25]
[Artist:: [[Genesis]] ]
[Genre:: Pop Rock]
[Played:: 8]
[Album:: [[Genesis (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[That's All]]
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
		intensity: page["That's_All"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
