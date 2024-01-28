---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Hunting High and Low (1985).jpg]]"
---
[Time:: 3:07]
[Artist:: [[A-ha]] ]
[Genre:: Synth-Pop]
[Played:: 2]
[Album:: [[Hunting High and Low (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Is Reason]]
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
		intensity: page["Love_Is_Reason"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
