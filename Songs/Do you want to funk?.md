---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:09]
[Artist:: [[Sylvester]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Do you want to funk?]]
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
		intensity: page["Do_you_want_to_funk?"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
