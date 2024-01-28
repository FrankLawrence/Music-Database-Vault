---
tags: Song  
banner: "![[The Monkees Greatest Hits (1967).jpg]]"
---
[Time:: 2:52]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Monkees Greatest Hits (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Words]]
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
		intensity: page["Words"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
