---
tags: Song ⭐⭐⭐ 
banner: "![[Piano Man (1975).jpg]]"
---
[Time:: 6:04]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Piano Man (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[New York State Of Mind]]
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
		intensity: page["New_York_State_Of_Mind"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
