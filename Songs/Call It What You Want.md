---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Torches (2011).jpg]]"
---
[Time:: 3:59]
[Artist:: [[Foster the People]] ]
[Genre:: Psychedelic Pop]
[Played:: 9]
[Album:: [[Torches (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Call It What You Want]]
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
		intensity: page["Call_It_What_You_Want"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
