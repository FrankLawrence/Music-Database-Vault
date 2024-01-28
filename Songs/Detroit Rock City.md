---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Destroyer (1976).jpg]]"
---
[Time:: 3:38]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: 24]
[Album:: [[Destroyer (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Detroit Rock City]]
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
		intensity: page["Detroit_Rock_City"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
