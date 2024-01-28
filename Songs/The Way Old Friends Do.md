---
tags: Song  
banner: "![[Super trouper (1980).jpg]]"
---
[Time:: 2:55]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Super trouper (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Way Old Friends Do]]
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
		intensity: page["The_Way_Old_Friends_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
