---
tags: Song ⭐⭐ 
banner: "![[All The Best (1980).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Paul McCartney]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[All The Best (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Coming Up]]
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
		intensity: page["Coming_Up"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
