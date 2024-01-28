---
tags: Song  
banner: "![[1 (2000).jpg]]"
---
[Time:: 2:20]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[1 (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Me Do]]
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
		intensity: page["Love_Me_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
