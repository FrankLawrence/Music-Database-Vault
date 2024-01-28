---
tags: Song  
banner: "![[Barry White's Greatest Hits (1975).jpg]]"
---
[Time:: 3:10]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 1]
[Album:: [[Barry White's Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I've Got So Much To GIve]]
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
		intensity: page["I've_Got_So_Much_To_GIve"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
