---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Violator (1990).jpg]]"
---
[Time:: 4:40]
[Artist:: [[Depeche Mode]] ]
[Genre:: Synth-Pop]
[Played:: 35]
[Album:: [[Violator (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Enjoy the Silence]]
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
		intensity: page["Enjoy_the_Silence"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
