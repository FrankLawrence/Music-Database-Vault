---
tags: Song  
banner: "![[Anthology 1 [Disc 2] (1963).jpg]]"
---
[Time:: 0:50]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Anthology 1 [Disc 2] (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Moonlight Bay]]
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
		intensity: page["Moonlight_Bay"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
