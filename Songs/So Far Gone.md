---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Some Kind of Trouble (2010).jpg]]"
---
[Time:: 3:33]
[Artist:: [[James Blunt]] ]
[Genre:: ]
[Played:: 4]
[Album:: [[Some Kind of Trouble (2010)]]]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[So Far Gone]]
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
		intensity: page["So_Far_Gone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
