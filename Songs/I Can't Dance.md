---
tags: Song ⭐⭐⭐ 
banner: "![[We can't Dance (1991).jpg]]"
---
[Time:: 4:50]
[Artist:: [[Genesis]] ]
[Genre:: Blues Rock]
[Played:: ]
[Album:: [[We can't Dance (1991)]]]
[Year:: 1991]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Can't Dance]]
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
		intensity: page["I_Can't_Dance"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
