---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Okie (1974).jpg]]"
---
[Time:: 2:05]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 6]
[Album:: [[Okie (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rock and Roll Records]]
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
		intensity: page["Rock_and_Roll_Records"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
