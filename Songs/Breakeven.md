---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Script (2008).jpg]]"
---
[Time:: 4:16]
[Artist:: [[The Script]] ]
[Genre:: Pop Rock]
[Played:: 3]
[Album:: [[The Script (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Breakeven]]
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
		intensity: page["Breakeven"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
