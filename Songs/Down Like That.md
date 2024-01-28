---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Dissimulation (2020).jpg]]"
---
[Time:: 2:55]
[Artist:: [[Ksi]] [[Rick Ross]] [[Lil Baby & S-X]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 2]
[Album:: [[Dissimulation (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Down Like That]]
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
		intensity: page["Down_Like_That"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
