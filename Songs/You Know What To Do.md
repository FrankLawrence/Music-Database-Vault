---
tags: Song  
banner: "![[Anthology 1 [Disc 2] (1964).jpg]]"
---
[Time:: 1:59]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Anthology 1 [Disc 2] (1964)]]]
[Year:: 1964]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Know What To Do]]
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
		intensity: page["You_Know_What_To_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
