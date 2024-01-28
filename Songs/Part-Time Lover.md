---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[In Square Circle (1985).jpg]]"
---
[Time:: 4:15]
[Artist:: [[Stevie Wonder]] ]
[Genre:: Pop]
[Played:: 27]
[Album:: [[In Square Circle (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Part-Time Lover]]
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
		intensity: page["Part-Time_Lover"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
