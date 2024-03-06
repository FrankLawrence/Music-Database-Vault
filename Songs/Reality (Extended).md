---
tags: Song ⭐⭐⭐ 

[Time:: 4:30]
[Artist:: [[Lost Frequencies]] [[Janieck Devy]] ]
[Genre:: Rock/Pop]
[Played:: ]
[Played:: 1]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Reality (Extended)]]
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
		intensity: page["Reality_(Extended)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
