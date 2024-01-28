---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:35]
[Artist:: [[Farid Bang]] ]
[Genre:: ]
[Played:: 1]
[Album:: ]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ching Cheng Hanji]]
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
		intensity: page["Ching_Cheng_Hanji"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
