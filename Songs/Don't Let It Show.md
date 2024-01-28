---
tags: Song  
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Let It Show]]
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
		intensity: page["Don't_Let_It_Show"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
