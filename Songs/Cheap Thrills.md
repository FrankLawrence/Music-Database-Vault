---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[This Is Acting (2016).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Sia]] ]
[Genre:: Synth-Pop]
[Played:: 2]
[Album:: [[This Is Acting (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cheap Thrills]]
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
		intensity: page["Cheap_Thrills"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
