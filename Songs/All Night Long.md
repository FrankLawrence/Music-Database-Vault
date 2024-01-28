---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Can't Slow Down (1992).jpg]]"
---
[Time:: 4:20]
[Artist:: [[Lionel Richie]] ]
[Genre:: Reggae]
[Played:: 5]
[Album:: [[Can't Slow Down (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All Night Long]]
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
		intensity: page["All_Night_Long"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
