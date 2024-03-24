---
tags: Song  
banner: "![[1967-1970 (1973).jpg]]"
---
[Time:: 3:00]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[1967-1970 (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Fool On The Hill]]
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
		intensity: page["The_Fool_On_The_Hill"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
