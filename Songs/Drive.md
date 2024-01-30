---
tags: Song  
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 4:00]
[Artist:: [[The Cars]] ]
[Genre:: Pop]
[Played:: 8]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Drive]]
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
		intensity: page["Drive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
