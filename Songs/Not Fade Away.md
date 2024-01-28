---
tags: Song  
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (1964).jpg]]"
---
[Time:: 1:48]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Not Fade Away]]
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
		intensity: page["Not_Fade_Away"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
