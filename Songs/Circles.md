---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hollywood's Bleeding (2019).jpg]]"
---
[Time:: 3:46]
[Artist:: [[Post Malone]] ]
[Genre:: Pop Rock]
[Played:: 9]
[Album:: [[Hollywood's Bleeding (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Circles]]
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
		intensity: page["Circles"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
