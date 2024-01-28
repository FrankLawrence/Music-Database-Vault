---
tags: Song ⭐⭐⭐⭐ 

[Time:: 4:44]
[Artist:: [[Fallen Lights]] ]
[Genre:: ]
[Played:: 2]
[Album:: ]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All We Are]]
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
		intensity: page["All_We_Are"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
