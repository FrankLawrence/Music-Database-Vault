---
tags: Song  
banner: "![[1967-1970 (1973).jpg]]"
---
[Time:: 3:25]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[1967-1970 (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Revolution]]
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
		intensity: page["Revolution"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
