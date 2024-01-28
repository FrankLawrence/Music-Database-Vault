---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[So Into You  (1997).jpg]]"
---
[Time:: 4:15]
[Artist:: [[Atlanta Rhythm Section]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[So Into You  (1997)]]]
[Year:: 1997]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Homesick]]
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
		intensity: page["Homesick"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
