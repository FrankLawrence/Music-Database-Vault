---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Pipes of peace (1983).jpg]]"
---
[Time:: 3:57]
[Artist:: [[Paul McCartney]] [[Michael Jackson]] ]
[Genre:: Pop]
[Played:: 43]
[Album:: [[Pipes of peace (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Say Say Say]]
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
		intensity: page["Say_Say_Say"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
