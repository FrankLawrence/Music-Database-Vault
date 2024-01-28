---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Arrival (1976).jpg]]"
---
[Time:: 3:48]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Arrival (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dancing Queen]]
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
		intensity: page["Dancing_Queen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
