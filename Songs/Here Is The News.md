---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Time (1981).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Progressive Rock]
[Played:: 19]
[Album:: [[Time (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Here Is The News]]
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
		intensity: page["Here_Is_The_News"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
