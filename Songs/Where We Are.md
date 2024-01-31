---
tags: Song ⭐⭐⭐⭐⭐ 💔
banner: 
---
[Time:: 4:04]
[Artist:: [[Ryos]] [[Karra]] ]
[Genre:: ]
[Played:: 22]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Where We Are]]
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
		intensity: page["Where_We_Are"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
