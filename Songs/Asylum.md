---
tags: Song  
banner: "![[Crime of the Century (1974).jpg]]"
---
[Time:: 6:50]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 1]
[Album:: [[Crime of the Century (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Asylum]]
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
		intensity: page["Asylum"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
