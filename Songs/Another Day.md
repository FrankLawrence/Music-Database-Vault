---
tags: Song ⭐⭐⭐ 
banner: "![[All The Best (1971).jpg]]"
---
[Time:: 3:42]
[Artist:: [[Paul McCartney]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[All The Best (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Another Day]]
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
		intensity: page["Another_Day"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
