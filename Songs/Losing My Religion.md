---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Out of Time (1991).jpg]]"
---
[Time:: 4:54]
[Artist:: [[R.E.M.]] ]
[Genre:: Alternative Rock]
[Played:: 10]
[Album:: [[Out of Time (1991)]]]
[Year:: 1991]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Losing My Religion]]
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
		intensity: page["Losing_My_Religion"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
