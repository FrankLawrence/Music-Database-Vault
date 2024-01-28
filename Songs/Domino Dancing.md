---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Introspective (1988).jpg]]"
---
[Time:: 4:18]
[Artist:: [[Pet Shop Boys]] ]
[Genre:: Synth-Pop]
[Played:: 10]
[Album:: [[Introspective (1988)]]]
[Year:: 1988]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Domino Dancing]]
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
		intensity: page["Domino_Dancing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
