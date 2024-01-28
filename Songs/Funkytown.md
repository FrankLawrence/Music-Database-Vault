---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Mouth To Mouth (1979).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Lipps Inc.]] ]
[Genre:: Disco]
[Played:: 5]
[Album:: [[Mouth To Mouth (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Funkytown]]
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
		intensity: page["Funkytown"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
