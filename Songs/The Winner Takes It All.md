---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Super Trouper (1980).jpg]]"
---
[Time:: 4:56]
[Artist:: [[ABBA]] ]
[Genre:: Electronic, Pop]
[Played:: 8]
[Album:: [[Super Trouper (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Winner Takes It All]]
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
		intensity: page["The_Winner_Takes_It_All"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
