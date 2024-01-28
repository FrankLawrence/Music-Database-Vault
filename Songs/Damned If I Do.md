---
tags: Song  
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 3:35]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Damned If I Do]]
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
		intensity: page["Damned_If_I_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
