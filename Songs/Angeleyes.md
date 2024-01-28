---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Greatest Hits Vol. 2 (1979).jpg]]"
---
[Time:: 4:19]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 32]
[Album:: [[Greatest Hits Vol. 2 (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Angeleyes]]
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
		intensity: page["Angeleyes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
