---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Humanz (2017).jpg]]"
---
[Time:: 3:24]
[Artist:: [[Gorillaz]] [[Kali Uchis]] ]
[Genre:: Electropop]
[Played:: 23]
[Album:: [[Humanz (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[She’s My Collar]]
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
		intensity: page["She’s_My_Collar"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
