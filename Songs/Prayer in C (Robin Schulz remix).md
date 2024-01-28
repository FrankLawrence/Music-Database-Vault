---
tags: Song ⭐⭐⭐ 

[Time:: 3:14]
[Artist:: [[Lilly Wood & The Prick]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Prayer in C (Robin Schulz remix)]]
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
		intensity: page["Prayer_in_C_(Robin_Schulz_remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
