---
tags: Song  
banner: "![[Best Of Bowie (2002).jpg]]"
---
[Time:: 3:57]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Best Of Bowie (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Slow Burn (Radio Edition)]]
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
		intensity: page["Slow_Burn_(Radio_Edition)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
