---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Tango in the Night (1987).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Fleetwood Mac]] ]
[Genre:: Soft Rock]
[Played:: 24]
[Album:: [[Tango in the Night (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Everywhere]]
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
		intensity: page["Everywhere"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
