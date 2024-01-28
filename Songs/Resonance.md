---
tags: Song ⭐⭐⭐ 
banner: ""
---
[Time:: 3:33]
[Artist:: [[HOME]] ]
[Genre:: Instrumental]
[Played:: 12]
[Album:: [[]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Resonance]]
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
		intensity: page["Resonance"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
