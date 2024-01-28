---
tags: Song ⭐⭐ 
banner: "![[Greatest Hits Vol. 2 (1979).jpg]]"
---
[Time:: 3:20]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Greatest Hits Vol. 2 (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lovelight]]
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
		intensity: page["Lovelight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
