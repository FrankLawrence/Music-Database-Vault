---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Division Bell (1994).jpg]]"
---
[Time:: 5:57]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 48]
[Album:: [[The Division Bell (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cluster One]]
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
		intensity: page["Cluster_One"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
