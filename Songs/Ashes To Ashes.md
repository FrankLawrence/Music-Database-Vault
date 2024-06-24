---
tags: Song  
banner: "![[Best Of Bowie (1980).jpg]]"
---
[Time:: 3:37]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 12]
[Album:: [[Best Of Bowie (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ashes To Ashes]]
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
		intensity: page["Ashes_To_Ashes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
