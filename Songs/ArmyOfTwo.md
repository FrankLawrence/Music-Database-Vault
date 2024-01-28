---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Rigt Place Right Time (2012).jpg]]"
---
[Time:: 4:47]
[Artist:: [[Olly Murs]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Rigt Place Right Time (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[ArmyOfTwo]]
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
		intensity: page["ArmyOfTwo"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
