---
tags: Song  
banner: "![[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (1965).jpg]]"
---
[Time:: 2:55]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Rolled Gold Plus: Very Best Of The Rolling Stones [Disc 1] (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Get Off Of My Cloud]]
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
		intensity: page["Get_Off_Of_My_Cloud"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
