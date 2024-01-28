---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Blame it on Baby (2020).jpg]]"
---
[Time:: 3:02]
[Artist:: [[Dababy]] [[Roddy Ricch]] ]
[Genre:: Hip-Hop/Rap]
[Played:: ]
[Album:: [[Blame it on Baby (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rockstar]]
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
		intensity: page["Rockstar"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
