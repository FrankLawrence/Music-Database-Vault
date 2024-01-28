---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Night Visions (2013).jpg]]"
---
[Time:: 3:56]
[Artist:: [[Imagine Dragons]] ]
[Genre:: Pop Rock]
[Played:: ]
[Album:: [[Night Visions (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Demons]]
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
		intensity: page["Demons"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
