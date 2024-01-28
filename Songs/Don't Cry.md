---
tags: Song  
banner: "![[At Worse...The Best Of Boy George And Culture Club (1993).jpg]]"
---
[Time:: 4:07]
[Artist:: [[Culture Club]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[At Worse...The Best Of Boy George And Culture Club (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Cry]]
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
		intensity: page["Don't_Cry"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
