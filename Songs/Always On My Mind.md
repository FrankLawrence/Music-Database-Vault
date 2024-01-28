---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Introspective (1988).jpg]]"
---
[Time:: 5:19]
[Artist:: [[Pet Shop Boys]] ]
[Genre:: Synth-Pop]
[Played:: 17]
[Album:: [[Introspective (1988)]]]
[Year:: 1988]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Always On My Mind]]
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
		intensity: page["Always_On_My_Mind"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
