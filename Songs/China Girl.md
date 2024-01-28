---
tags: Song  
banner: "![[Best Of Bowie (1983).jpg]]"
---
[Time:: 4:19]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Best Of Bowie (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[China Girl]]
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
		intensity: page["China_Girl"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
