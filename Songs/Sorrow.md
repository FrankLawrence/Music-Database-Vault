---
tags: Song  
banner: "![[Best Of Bowie (1973).jpg]]"
---
[Time:: 2:55]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 37]
[Album:: [[Best Of Bowie (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sorrow]]
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
		intensity: page["Sorrow"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
