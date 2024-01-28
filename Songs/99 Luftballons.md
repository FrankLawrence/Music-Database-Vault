---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Nena (1983).jpg]]"
---
[Time:: 3:53]
[Artist:: [[Nena]] ]
[Genre:: New Wave]
[Played:: 3]
[Album:: [[Nena (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[99 Luftballons]]
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
		intensity: page["99_Luftballons"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
