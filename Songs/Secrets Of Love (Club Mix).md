---
tags: Song ⭐ 
banner: "![[The Very Best Of Sandra [Disc 2] (2016).jpg]]"
---
[Time:: 3:59]
[Artist:: [[DJ Bobo & Sandra]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Very Best Of Sandra [Disc 2] (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Secrets Of Love (Club Mix)]]
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
		intensity: page["Secrets_Of_Love_(Club_Mix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
