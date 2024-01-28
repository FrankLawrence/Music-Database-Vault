---
tags: Song  
banner: "![[The Monkees Greatest Hits (1987).jpg]]"
---
[Time:: 3:44]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Monkees Greatest Hits (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heart And Soul]]
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
		intensity: page["Heart_And_Soul"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
