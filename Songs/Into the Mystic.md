---
tags: Song  
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Van Morrison]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Ultimate FM Gold (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Into the Mystic]]
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
		intensity: page["Into_the_Mystic"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
