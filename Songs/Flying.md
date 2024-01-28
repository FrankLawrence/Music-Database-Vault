---
tags: Song  
banner: "![[Magical Mystery Tour (1967).jpg]]"
---
[Time:: 2:16]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[Magical Mystery Tour (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Flying]]
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
		intensity: page["Flying"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
