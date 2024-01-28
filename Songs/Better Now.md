---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Beerbongs & Bentleys (2018).jpg]]"
---
[Time:: 3:52]
[Artist:: [[Post Malone]] ]
[Genre:: R&B]
[Played:: 21]
[Album:: [[Beerbongs & Bentleys (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Better Now]]
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
		intensity: page["Better_Now"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
