---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Division Bell (1994).jpg]]"
---
[Time:: 4:17]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 21]
[Album:: [[The Division Bell (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Great Day for Freedom]]
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
		intensity: page["A_Great_Day_for_Freedom"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
