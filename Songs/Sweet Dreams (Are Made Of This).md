---
tags: Song  
banner: "![[Sweet Dreams (Are Made Of This) (1983).jpg]]"
---
[Time:: 3:36]
[Artist:: [[Eurythmics]] ]
[Genre:: Rock/Pop]
[Played:: ]
[Album:: [[Sweet Dreams (Are Made Of This) (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sweet Dreams (Are Made Of This)]]
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
		intensity: page["Sweet_Dreams_(Are_Made_Of_This)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
