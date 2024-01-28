---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Devil May Cry 5 Soundtrack (2020).jpg]]"
---
[Time:: 9:42]
[Artist:: [[Casey Edwards]] [[Victor Borba]] ]
[Genre:: Soundtrack]
[Played:: 52]
[Album:: [[Devil May Cry 5 Soundtrack (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bury the Light]]
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
		intensity: page["Bury_the_Light"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
