---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Night Visions (2012).jpg]]"
---
[Time:: 4:21]
[Artist:: [[Imagine Dragons]] ]
[Genre:: Alternative Rock]
[Played:: 1]
[Album:: [[Night Visions (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Radioactive]]
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
		intensity: page["Radioactive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
