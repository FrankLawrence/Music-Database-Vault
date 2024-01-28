---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Jazz (1977).jpg]]"
---
[Time:: 3:04]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[Jazz (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bicycle Race]]
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
		intensity: page["Bicycle_Race"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
