---
tags: Song  
banner: "![[Magical Mystery Tour (1967).jpg]]"
---
[Time:: 2:28]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[Magical Mystery Tour (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Your Mother Should Know]]
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
		intensity: page["Your_Mother_Should_Know"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
