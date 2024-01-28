---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Best of Herman and the Hermits (1964).jpg]]"
---
[Time:: 2:34]
[Artist:: [[Herman's Hermits]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Best of Herman and the Hermits (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm into Something Good]]
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
		intensity: page["I'm_into_Something_Good"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
