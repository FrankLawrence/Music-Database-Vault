---
tags: Song  
banner: "![[Help! (1965).jpg]]"
---
[Time:: 2:05]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Help! (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Another Girl]]
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
		intensity: page["Another_Girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
