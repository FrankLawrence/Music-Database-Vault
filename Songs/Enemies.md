---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Hollywood's Bleeding (2019).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Post Malone]] [[Dababy]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 6]
[Album:: [[Hollywood's Bleeding (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Enemies]]
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
		intensity: page["Enemies"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
