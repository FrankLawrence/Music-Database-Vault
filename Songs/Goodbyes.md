---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hollywood's Bleeding (2019).jpg]]"
---
[Time:: 2:54]
[Artist:: [[Post Malone]] [[Yount Thug]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 6]
[Album:: [[Hollywood's Bleeding (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Goodbyes]]
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
		intensity: page["Goodbyes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
