---
tags: Song ⭐ 
banner: "![[At Worse...The Best Of Boy George And Culture Club (1984).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Culture Club]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[At Worse...The Best Of Boy George And Culture Club (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Is Love]]
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
		intensity: page["Love_Is_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
