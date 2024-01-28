---
tags: Song ⭐⭐⭐⭐ 

[Time:: 17:40]
[Artist:: [[Olly James]] ]
[Genre:: ]
[Played:: 13]
[Album:: ]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Again]]
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
		intensity: page["Love_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
