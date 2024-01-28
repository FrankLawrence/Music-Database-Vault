---
tags: Song  
banner: "![[The Monkees Greatest Hits (1967).jpg]]"
---
[Time:: 2:35]
[Artist:: [[The Monkees]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[The Monkees Greatest Hits (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Girl I Knew Somewhere]]
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
		intensity: page["The_Girl_I_Knew_Somewhere"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
