---
tags: Song  
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 2:45]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Pyromania]]
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
		intensity: page["Pyromania"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
