---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Division Bell (1994).jpg]]"
---
[Time:: 5:02]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 18]
[Album:: [[The Division Bell (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Take it Back]]
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
		intensity: page["Take_it_Back"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
