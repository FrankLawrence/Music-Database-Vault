---
tags: Song ⭐⭐⭐ 

[Time:: 3:39]
[Artist:: [[Robin_Schulz]] ]
[Genre:: Rock Pop]
[Played:: 1]
[Album:: ]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sugar]]
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
		intensity: page["Sugar"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
