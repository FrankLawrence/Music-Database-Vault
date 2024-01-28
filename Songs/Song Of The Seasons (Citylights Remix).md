---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 2:03]
[Artist:: [[Citylights]] ]
[Genre:: ]
[Played:: 23]
[Album:: ]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Song Of The Seasons (Citylights Remix)]]
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
		intensity: page["Song_Of_The_Seasons_(Citylights_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
