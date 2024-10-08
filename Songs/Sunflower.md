---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Hollywood's Bleeding (2018).jpg]]"
---
[Time:: 2:38]
[Artist:: [[Post Malone]] [[Swae Lee]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 30]
[Album:: [[Hollywood's Bleeding (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sunflower]]
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
		intensity: page["Sunflower"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
