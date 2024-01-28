---
tags: Song ⭐⭐⭐ 
banner: "![[Piano Man (1989).jpg]]"
---
[Time:: 4:31]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Piano Man (1989)]]]
[Year:: 1989]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We Didn't Start The Fire]]
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
		intensity: page["We_Didn't_Start_The_Fire"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
