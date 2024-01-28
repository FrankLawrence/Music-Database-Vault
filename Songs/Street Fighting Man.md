---
tags: Song ⭐⭐ 
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (2007).jpg]]"
---
[Time:: 3:16]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Street Fighting Man]]
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
		intensity: page["Street_Fighting_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
