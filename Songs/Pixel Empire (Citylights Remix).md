---
tags: Song ⭐⭐⭐⭐⭐ 
banner: 
---
[Time:: 4:10]
[Artist:: [[Citylights]] ]
[Genre:: ]
[Played:: 28]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Pixel Empire (Citylights Remix)]]
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
		intensity: page["Pixel_Empire_(Citylights_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
