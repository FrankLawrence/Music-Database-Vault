---
tags: Song  
banner: "![[Jazz (2001).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Dennis Taylor]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Jazz (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Smile]]
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
		intensity: page["Smile"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
