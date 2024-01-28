---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:58]
[Artist:: [[Producer Snafu]] ]
[Genre:: ]
[Played:: 17]
[Album:: ]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Chicken Attack]]
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
		intensity: page["Chicken_Attack"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
