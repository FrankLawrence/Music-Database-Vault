---
tags: Song  
banner: "![[Help! (1965).jpg]]"
---
[Time:: 2:37]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Help! (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Like Me Too Much]]
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
		intensity: page["You_Like_Me_Too_Much"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
