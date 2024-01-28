---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Piano Man (1978).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 52]
[Album:: [[Piano Man (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Honesty]]
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
		intensity: page["Honesty"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
