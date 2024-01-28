---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Time (1981).jpg]]"
---
[Time:: 3:07]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 9]
[Album:: [[Time (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hold On Tight]]
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
		intensity: page["Hold_On_Tight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
