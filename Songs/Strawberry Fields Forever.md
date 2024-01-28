---
tags: Song  
banner: "![[Magical Mystery Tour (1967).jpg]]"
---
[Time:: 4:07]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[Magical Mystery Tour (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Strawberry Fields Forever]]
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
		intensity: page["Strawberry_Fields_Forever"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
