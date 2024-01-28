---
tags: Song ⭐ 💔
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (1969).jpg]]"
---
[Time:: 3:01]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 2] (1969)]]]
[Year:: 1969]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Honky Tonk Women]]
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
		intensity: page["Honky_Tonk_Women"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
