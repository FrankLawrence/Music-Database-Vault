---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 1:53]
[Artist:: [[]] ]
[Genre:: ]
[Played:: 12]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Omae Wa Mou]]
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
		intensity: page["Omae_Wa_Mou"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
