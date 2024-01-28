---
tags: Song  
banner: "![[Let It Be (1970).jpg]]"
---
[Time:: 0:50]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[Let It Be (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dig It]]
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
		intensity: page["Dig_It"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
