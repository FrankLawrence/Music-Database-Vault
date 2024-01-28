---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 4:31]
[Artist:: [[SIDO]] ]
[Genre:: ]
[Played:: 5]
[Album:: ]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sido - Hollywood]]
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
		intensity: page["Sido_-_Hollywood"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
