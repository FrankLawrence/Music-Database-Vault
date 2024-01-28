---
tags: Song  
banner: "![[Best Of Bowie (1972).jpg]]"
---
[Time:: 4:06]
[Artist:: [[David Bowie]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Best Of Bowie (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Jean Genie]]
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
		intensity: page["The_Jean_Genie"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
