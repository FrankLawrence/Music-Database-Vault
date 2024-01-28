---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Reload (1999).jpg]]"
---
[Time:: 3:29]
[Artist:: [[Tom Jones & Mousse T.]] ]
[Genre:: Pop Rock]
[Played:: 3]
[Album:: [[Reload (1999)]]]
[Year:: 1999]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sexbomb]]
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
		intensity: page["Sexbomb"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
