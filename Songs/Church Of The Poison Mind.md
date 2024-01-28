---
tags: Song  
banner: "![[At Worse...The Best Of Boy George And Culture Club (1983).jpg]]"
---
[Time:: 3:31]
[Artist:: [[Culture Club]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[At Worse...The Best Of Boy George And Culture Club (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Church Of The Poison Mind]]
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
		intensity: page["Church_Of_The_Poison_Mind"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
