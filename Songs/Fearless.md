---
tags: Song ⭐⭐⭐ 
banner: "![[Meddle (1971).jpg]]"
---
[Time:: 6:08]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 9]
[Album:: [[Meddle (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fearless]]
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
		intensity: page["Fearless"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
