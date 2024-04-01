---
tags: Song  
banner: "![[Goodbye Yellow Brick Road (1973).jpg]]"
---
[Time:: 5:59]
[Artist:: [[Elton John]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Goodbye Yellow Brick Road (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I've seen that movie too]]
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
		intensity: page["I've_seen_that_movie_too"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```