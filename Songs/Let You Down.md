---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Perception (2017).jpg]]"
---
[Time:: 3:32]
[Artist:: [[NF]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 8]
[Album:: [[Perception (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let You Down]]
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
		intensity: page["Let_You_Down"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
