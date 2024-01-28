---
tags: Song  
banner: "![[At Worse...The Best Of Boy George And Culture Club (1983).jpg]]"
---
[Time:: 4:55]
[Artist:: [[Culture Club]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[At Worse...The Best Of Boy George And Culture Club (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Victims]]
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
		intensity: page["Victims"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
