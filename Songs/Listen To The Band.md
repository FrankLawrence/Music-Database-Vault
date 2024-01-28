---
tags: Song  
banner: "![[The Monkees Greatest Hits (1968).jpg]]"
---
[Time:: 2:34]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Monkees Greatest Hits (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Listen To The Band]]
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
		intensity: page["Listen_To_The_Band"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
