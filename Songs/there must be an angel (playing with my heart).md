---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Greatest Hits (1985).jpg]]"
---
[Time:: 5:23]
[Artist:: [[Eurythmics]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Greatest Hits (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[there must be an angel (playing with my heart)]]
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
		intensity: page["there_must_be_an_angel_(playing_with_my_heart)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
