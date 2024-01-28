---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[All Over the Place (2020).jpg]]"
---
[Time:: 3:19]
[Artist:: [[KSI]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 6]
[Album:: [[All Over the Place (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don’t Play]]
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
		intensity: page["Don’t_Play"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
