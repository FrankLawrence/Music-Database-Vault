---
tags: Song ⭐⭐⭐⭐ 

[Time:: 47:17]
[Artist:: [[hiphop]] ]
[Genre:: ]
[Played:: 9]
[Album:: ]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Late Nights Vol. 1  A Chill Hip Hop RB Mix 2016]]
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
		intensity: page["Late_Nights_Vol._1__A_Chill_Hip_Hop_RB_Mix_2016"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
