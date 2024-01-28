---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Cross Road (1994).jpg]]"
---
[Time:: 5:45]
[Artist:: [[Bon Jovi]] ]
[Genre:: Rock]
[Played:: 8]
[Album:: [[Cross Road (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Keep The Faith]]
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
		intensity: page["Keep_The_Faith"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
