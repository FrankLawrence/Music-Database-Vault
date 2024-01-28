---
tags: Song ⭐⭐⭐ 
banner: "![[Labour of Love (1982).jpg]]"
---
[Time:: 3:24]
[Artist:: [[UB40]] ]
[Genre:: Reggae]
[Played:: ]
[Album:: [[Labour of Love (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Red Red Wine]]
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
		intensity: page["Red_Red_Wine"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
