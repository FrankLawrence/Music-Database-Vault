---
tags: Song  
banner: "![[Best Of Bowie (1972).jpg]]"
---
[Time:: 3:25]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Best Of Bowie (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Suffragette City]]
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
		intensity: page["Suffragette_City"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
