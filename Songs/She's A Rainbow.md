---
tags: Song ⭐⭐ 
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (1967).jpg]]"
---
[Time:: 4:15]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[She's A Rainbow]]
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
		intensity: page["She's_A_Rainbow"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
