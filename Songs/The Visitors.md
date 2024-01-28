---
tags: Song  
banner: "![[The Visitors (1981).jpg]]"
---
[Time:: 4:29]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Visitors (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Visitors]]
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
		intensity: page["The_Visitors"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
