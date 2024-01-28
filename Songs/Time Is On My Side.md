---
tags: Song  
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (2007).jpg]]"
---
[Time:: 2:59]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Time Is On My Side]]
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
		intensity: page["Time_Is_On_My_Side"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
