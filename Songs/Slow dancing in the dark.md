---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Ballads 1 (2018).jpg]]"
---
[Time:: 3:27]
[Artist:: [[Joji]] ]
[Genre:: R&B/Soul]
[Played:: 35]
[Album:: [[Ballads 1 (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Slow dancing in the dark]]
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
		intensity: page["Slow_dancing_in_the_dark"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
