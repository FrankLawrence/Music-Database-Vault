---
tags: Song ⭐⭐⭐ 

[Time:: 3:21]
[Artist:: [[Tim Bendzko]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: ]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Nur noch kurz die Welt retten]]
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
		intensity: page["Nur_noch_kurz_die_Welt_retten"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
