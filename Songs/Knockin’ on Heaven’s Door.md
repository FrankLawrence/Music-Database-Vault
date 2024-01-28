---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Use Your Illusion II (1992).jpg]]"
---
[Time:: 5:36]
[Artist:: [[Guns N' Roses]] ]
[Genre:: Hard Rock]
[Played:: 7]
[Album:: [[Use Your Illusion II (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Knockin’ on Heaven’s Door]]
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
		intensity: page["Knockin’_on_Heaven’s_Door"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
