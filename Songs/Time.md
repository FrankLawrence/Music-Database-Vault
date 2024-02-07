---
tags: Song  
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 5:00]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: 42]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Time]]
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
		intensity: page["Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
