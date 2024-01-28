---
tags: Song  
banner: "![[A Night at the Opera (1975).jpg]]"
---
[Time:: 4:02]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: ]
[Album:: [[A Night at the Opera (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sweet Lady]]
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
		intensity: page["Sweet_Lady"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
