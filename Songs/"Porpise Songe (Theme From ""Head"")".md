---
tags: Song  
banner: "![[The Monkees Greatest Hits (1968).jpg]]"
---
[Time:: 4:13]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Monkees Greatest Hits (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [["Porpise Songe (Theme From ""Head"")"]]
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
		intensity: page[""Porpise_Songe_(Theme_From_""Head"")""]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
