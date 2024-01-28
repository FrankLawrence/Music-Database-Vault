---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Don't Forget About Me, Demos (2018).jpg]]"
---
[Time:: 2:59]
[Artist:: [[Dominic Fike]] ]
[Genre:: Alternative Hip-Hop]
[Played:: 15]
[Album:: [[Don't Forget About Me, Demos (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[3 Nights]]
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
		intensity: page["3_Nights"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
