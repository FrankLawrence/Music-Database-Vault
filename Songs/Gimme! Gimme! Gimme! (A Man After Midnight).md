---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Hits Vol. 2 (1979).jpg]]"
---
[Time:: 4:49]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[Greatest Hits Vol. 2 (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Gimme! Gimme! Gimme! (A Man After Midnight)]]
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
		intensity: page["Gimme!_Gimme!_Gimme!_(A_Man_After_Midnight)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
