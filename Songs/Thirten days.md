---
tags: Song ⭐⭐⭐⭐ 
banner: "![[5 (1979).jpg]]"
---
[Time:: 2:50]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 7]
[Album:: [[5 (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Thirten days]]
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
		intensity: page["Thirten_days"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
