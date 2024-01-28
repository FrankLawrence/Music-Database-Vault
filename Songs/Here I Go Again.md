---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Saints & Sinners (1994).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Whitesnake]] ]
[Genre:: Metal]
[Played:: 34]
[Album:: [[Saints & Sinners (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Here I Go Again]]
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
		intensity: page["Here_I_Go_Again"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
