---
tags: Song ⭐⭐ 

[Time:: 3:35]
[Artist:: [[Lana Del Ray & Cedric Gervais]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Summertime Sadness]]
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
		intensity: page["Summertime_Sadness"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
