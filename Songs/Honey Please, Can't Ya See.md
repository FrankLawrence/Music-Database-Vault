---
tags: Song  
banner: "![[Barry White's Greatest Hits (1975).jpg]]"
---
[Time:: 3:14]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 3]
[Album:: [[Barry White's Greatest Hits (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Honey Please, Can't Ya See]]
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
		intensity: page["Honey_Please,_Can't_Ya_See"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
