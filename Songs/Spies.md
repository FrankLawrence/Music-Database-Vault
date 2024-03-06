---
tags: Song  
banner: "![[Parachutes (2000).jpg]]"
---
[Time:: 5:19]
[Artist:: [[Coldplay]] ]
[Genre:: Alternative Rock]
[Played:: 31]
[Album:: [[Parachutes (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Spies]]
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
		intensity: page["Spies"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
