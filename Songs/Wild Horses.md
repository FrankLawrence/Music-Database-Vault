---
tags: Song ⭐⭐ 
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (1971).jpg]]"
---
[Time:: 5:42]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (1971)]]]
[Year:: 1971]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wild Horses]]
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
		intensity: page["Wild_Horses"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
