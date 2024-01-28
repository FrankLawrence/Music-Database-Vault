---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Best Of The Alan Parsons Project (1979).jpg]]"
---
[Time:: 4:21]
[Artist:: [[Alan Parsons Project]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[The Best Of The Alan Parsons Project (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Games People Play]]
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
		intensity: page["Games_People_Play"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
