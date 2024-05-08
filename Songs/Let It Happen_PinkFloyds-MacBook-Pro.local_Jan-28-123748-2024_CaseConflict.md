---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Currents (2015).jpg]]"
---
[Time:: 7:51]
[Artist:: [[Tame Impala]] ]
[Genre:: Psychedelic Pop]
[Played:: 40]
[Album:: [[Currents (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let it happen]]
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
		intensity: page["Let_it_happen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
