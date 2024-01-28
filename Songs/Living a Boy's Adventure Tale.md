---
tags: Song ⭐⭐⭐ 
banner: "![[Hunting High and Low (1985).jpg]]"
---
[Time:: 5:03]
[Artist:: [[A-ha]] ]
[Genre:: Synth-Pop]
[Played:: 1]
[Album:: [[Hunting High and Low (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Living a Boy's Adventure Tale]]
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
		intensity: page["Living_a_Boy's_Adventure_Tale"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
