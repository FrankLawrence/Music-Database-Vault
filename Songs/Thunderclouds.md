---
tags: Song ⭐⭐⭐⭐ 
banner: "![[LSD (2018).jpg]]"
---
[Time:: 3:10]
[Artist:: [[LSD]] ]
[Genre:: Dance-pop]
[Played:: 1]
[Album:: [[LSD (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Thunderclouds]]
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
		intensity: page["Thunderclouds"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
