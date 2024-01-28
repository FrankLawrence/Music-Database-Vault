---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:36]
[Artist:: [[Camila Cabello]] [[Young Thug]] ]
[Genre:: Blues/R&B]
[Played:: 1]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Havana]]
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
		intensity: page["Havana"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
