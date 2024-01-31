---
tags: Song ⭐⭐⭐⭐⭐ 
banner: 
---
[Time:: 4:26]
[Artist:: [[Citylights]] ]
[Genre:: ]
[Played:: 20]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bleed (Citylights Remix)]]
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
		intensity: page["Bleed_(Citylights_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
