---
tags: Song ⭐⭐⭐ 
banner: "![[Into the Light (1986).jpg]]"
---
[Time:: 4:05]
[Artist:: [[Chris de Burgh]] ]
[Genre:: Soft Rock]
[Played:: ]
[Album:: [[Into the Light (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lady in Red]]
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
		intensity: page["Lady_in_Red"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
