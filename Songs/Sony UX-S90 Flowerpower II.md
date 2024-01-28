---
tags: Song ⭐⭐ 
banner: "![[Sony UX-S90 Flowerpower II A and B ().jpg]]"
---
[Time:: 1:34:10]
[Artist:: [[Flowerpower II]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Sony UX-S90 Flowerpower II A and B ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sony UX-S90 Flowerpower II]]
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
		intensity: page["Sony_UX-S90_Flowerpower_II"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
