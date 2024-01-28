---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Grasshopper (1982).jpg]]"
---
[Time:: 2:49]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 13]
[Album:: [[Grasshopper (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[City girls]]
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
		intensity: page["City_girls"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
