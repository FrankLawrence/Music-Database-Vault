---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Spirit (2008).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Leona Lewis]] ]
[Genre:: Latino R&B-Pop]
[Played:: 1]
[Album:: [[Spirit (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Better In Time]]
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
		intensity: page["Better_In_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
