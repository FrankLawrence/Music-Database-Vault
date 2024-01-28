---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Outlandos d'Amour (1978).jpg]]"
---
[Time:: 3:15]
[Artist:: [[The Police]] ]
[Genre:: Rock/Pop]
[Played:: 2]
[Album:: [[Outlandos d'Amour (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[ROXANNE]]
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
		intensity: page["ROXANNE"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
