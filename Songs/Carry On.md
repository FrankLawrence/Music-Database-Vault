---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Shades (1981).jpg]]"
---
[Time:: 2:21]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 17]
[Album:: [[Shades (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Carry On]]
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
		intensity: page["Carry_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
