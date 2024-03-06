---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Dark Side of the Moon (1973).jpg]]"
---
[Time:: 2:13]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 23]
[Album:: [[The Dark Side of the Moon (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Eclipse]]
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
		intensity: page["Eclipse"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
