---
tags: Song  
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (1966).jpg]]"
---
[Time:: 3:59]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (1966)]]]
[Year:: 1966]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[19th Nervous Breakdown]]
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
		intensity: page["19th_Nervous_Breakdown"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
