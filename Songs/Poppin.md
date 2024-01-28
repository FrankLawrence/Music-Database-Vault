---
tags: Song ⭐⭐⭐ 
banner: "![[Dissimulation (2020).jpg]]"
---
[Time:: 3:32]
[Artist:: [[KSI]] [[Lil Pump & Smokepurp]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 1]
[Album:: [[Dissimulation (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Poppin]]
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
		intensity: page["Poppin"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
