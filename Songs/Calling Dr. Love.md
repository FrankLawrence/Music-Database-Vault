---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Rock and Roll Over (1976).jpg]]"
---
[Time:: 3:46]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: 27]
[Album:: [[Rock and Roll Over (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Calling Dr. Love]]
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
		intensity: page["Calling_Dr._Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
