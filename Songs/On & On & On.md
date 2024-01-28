---
tags: Song ⭐⭐⭐ 
banner: "![[Super trouper (1980).jpg]]"
---
[Time:: 3:39]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Super trouper (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[On & On & On]]
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
		intensity: page["On_Eyes_Without_A_Face_On_Eyes_Without_A_Face_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
