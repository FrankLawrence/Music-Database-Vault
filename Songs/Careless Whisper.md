---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Make It Big (1984).jpg]]"
---
[Time:: 6:34]
[Artist:: [[Wham!]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Make It Big (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Careless Whisper]]
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
		intensity: page["Careless_Whisper"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
