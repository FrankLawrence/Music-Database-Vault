---
tags: Song  
banner: "![[Parachutes (2000).jpg]]"
---
[Time:: 3:48]
[Artist:: [[Coldplay]] ]
[Genre:: Alternative Rock]
[Played:: 24]
[Album:: [[Parachutes (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sparks]]
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
		intensity: page["Sparks"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
