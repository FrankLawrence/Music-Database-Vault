---
tags: Song ⭐⭐⭐⭐ 
banner: "![[X&Y (2006).jpg]]"
---
[Time:: 4:25]
[Artist:: [[Coldplay]] ]
[Genre:: Pop Rock]
[Played:: 2]
[Album:: [[X&Y (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Hardest Part]]
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
		intensity: page["The_Hardest_Part"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
