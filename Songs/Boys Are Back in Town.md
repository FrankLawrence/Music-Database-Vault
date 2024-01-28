---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Jailbreak (1976).jpg]]"
---
[Time:: 2:22]
[Artist:: [[Thin Lizzy]] ]
[Genre:: Hard Rock]
[Played:: 11]
[Album:: [[Jailbreak (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Boys Are Back in Town]]
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
		intensity: page["Boys_Are_Back_in_Town"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
