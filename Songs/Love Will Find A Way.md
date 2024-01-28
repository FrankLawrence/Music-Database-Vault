---
tags: Song ⭐⭐ 
banner: "![[Can't Slow Down (1983).jpg]]"
---
[Time:: 5:54]
[Artist:: [[Lionel Richie]] ]
[Genre:: R&B]
[Played:: ]
[Album:: [[Can't Slow Down (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Will Find A Way]]
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
		intensity: page["Love_Will_Find_A_Way"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
