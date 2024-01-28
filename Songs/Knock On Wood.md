---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Knock On Wood (1979).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Amii Stewart]] ]
[Genre:: Electronic, Funk / Soul]
[Played:: 3]
[Album:: [[Knock On Wood (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Knock On Wood]]
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
		intensity: page["Knock_On_Wood"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
