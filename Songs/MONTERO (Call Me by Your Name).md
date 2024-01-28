---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[MONTERO (2021).jpg]]"
---
[Time:: 2:18]
[Artist:: [[Lil Nas X]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 41]
[Album:: [[MONTERO (2021)]]]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[MONTERO (Call Me by Your Name)]]
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
		intensity: page["MONTERO_(Call_Me_by_Your_Name)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
