---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Astroworld (2018).jpg]]"
---
[Time:: 3:31]
[Artist:: [[Travis Scott]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 20]
[Album:: [[Astroworld (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[COFFEE BEAN]]
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
		intensity: page["COFFEE_BEAN"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
