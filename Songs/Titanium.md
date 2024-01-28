---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Nothing but the Beat 2.0 (2012).jpg]]"
---
[Time:: 4:05]
[Artist:: [[David Guetta]] [[Sia]] ]
[Genre:: Electro House]
[Played:: 1]
[Album:: [[Nothing but the Beat 2.0 (2012)]]]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Titanium]]
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
		intensity: page["Titanium"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
