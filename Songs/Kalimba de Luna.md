---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Kalimba de Luna – 16 Happy Songs (1984).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Boney M]] ]
[Genre:: Pop]
[Played:: 42]
[Album:: [[Kalimba de Luna – 16 Happy Songs (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Kalimba de Luna]]
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
		intensity: page["Kalimba_de_Luna"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
