---
tags: Song  
banner: "![[Best Of Bowie (1986).jpg]]"
---
[Time:: 5:38]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Best Of Bowie (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Absolute Beginners]]
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
		intensity: page["Absolute_Beginners"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
