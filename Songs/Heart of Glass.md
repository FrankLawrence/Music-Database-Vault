---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Parallel Lines (1979).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Blondie]] ]
[Genre:: New Wave]
[Played:: 5]
[Album:: [[Parallel Lines (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heart of Glass]]
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
		intensity: page["Heart_of_Glass"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
