---
tags: Song  
banner: "![[Help! (1965).jpg]]"
---
[Time:: 2:35]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 6]
[Album:: [[Help! (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Night Before]]
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
		intensity: page["The_Night_Before"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
