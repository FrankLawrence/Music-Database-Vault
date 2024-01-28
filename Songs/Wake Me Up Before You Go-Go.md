---
tags: Song ⭐⭐⭐ 
banner: "![[Make It Big (1984).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Wham!]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Make It Big (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wake Me Up Before You Go-Go]]
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
		intensity: page["Wake_Me_Up_Before_You_Go-Go"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
