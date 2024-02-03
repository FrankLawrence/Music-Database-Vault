---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Piano Man (1977).jpg]]"
---
[Time:: 3:30]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 69]
[Album:: [[Piano Man (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Movin' Out (Anthony's Song)]]
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
		intensity: page["Movin'_Out_(Anthony's_Song)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
