---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[5 (1979).jpg]]"
---
[Time:: 2:14]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 8]
[Album:: [[5 (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't cry sister]]
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
		intensity: page["Don't_cry_sister"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
