---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:21]
[Artist:: [[Martin Garrix & Justin Mylo]] [[Dewain Whitmore]] ]
[Genre:: Progressive House]
[Played:: 40]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Burn Out]]
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
		intensity: page["Burn_Out"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
