---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Escape (1981).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Journey]] ]
[Genre:: Rock]
[Played:: 21]
[Album:: [[Escape (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Stop Believin']]
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
		intensity: page["Don't_Stop_Believin'"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
