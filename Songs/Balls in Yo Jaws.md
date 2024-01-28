---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 1:19]
[Artist:: [[Frank Sinatra]] ]
[Genre:: ]
[Played:: 14]
[Album:: ]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Balls in Yo Jaws]]
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
		intensity: page["Balls_in_Yo_Jaws"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
