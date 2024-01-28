---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Piano Man (1973).jpg]]"
---
[Time:: 4:37]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Piano Man (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Piano Man]]
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
		intensity: page["Piano_Man"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
