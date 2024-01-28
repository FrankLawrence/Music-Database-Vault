---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Dean Martin ().jpg]]"
---
[Time:: 3:06]
[Artist:: [[Dean Martin]] ]
[Genre:: Easy Listening]
[Played:: ]
[Album:: [[Dean Martin ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[That's Amore]]
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
		intensity: page["That's_Amore"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
