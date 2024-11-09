---
tags: Song ⭐⭐⭐ 
banner: "![[The Endless River (2014).jpg]]"
---
[Time:: 1:35]
[Artist:: [[Pink Floyd]] ]
[Genre:: Psychedelic]
[Played:: 38]
[Album:: [[The Endless River (2014)]]]
[Year:: 2014]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Autumn '68]]
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
		intensity: page["Autumn_'68"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
