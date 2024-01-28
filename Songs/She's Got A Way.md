---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Piano Man (1981).jpg]]"
---
[Time:: 3:00]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 36]
[Album:: [[Piano Man (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[She's Got A Way]]
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
		intensity: page["She's_Got_A_Way"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
