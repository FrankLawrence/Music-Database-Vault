---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Gangsta's Paradise (1995).jpg]]"
---
[Time:: 4:14]
[Artist:: [[Coolio]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 2]
[Album:: [[Gangsta's Paradise (1995)]]]
[Year:: 1995]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Gangsta's Paradise]]
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
		intensity: page["Gangsta's_Paradise"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
