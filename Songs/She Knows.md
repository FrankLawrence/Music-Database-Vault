---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Born Sinner (2013).jpg]]"
---
[Time:: 4:59]
[Artist:: [[J. Cole]] [[Amber Coffman & Cults]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 6]
[Album:: [[Born Sinner (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[She Knows]]
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
		intensity: page["She_Knows"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
