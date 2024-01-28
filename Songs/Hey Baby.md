---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of J.J. Cale (2005).jpg]]"
---
[Time:: 3:18]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 1]
[Album:: [[The Very Best Of J.J. Cale (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hey Baby]]
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
		intensity: page["Hey_Baby"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
