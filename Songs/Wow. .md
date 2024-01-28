---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hollywood's Bleeding (2018).jpg]]"
---
[Time:: 2:31]
[Artist:: [[Post Malone]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 2]
[Album:: [[Hollywood's Bleeding (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wow. ]]
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
		intensity: page["Wow._"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
