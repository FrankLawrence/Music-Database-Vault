---
tags: Song ⭐⭐⭐ 
banner: "![[Beauty Behind the Madness (2015).jpg]]"
---
[Time:: 3:36]
[Artist:: [[The Weeknd]] ]
[Genre:: Disco funk]
[Played:: 2]
[Album:: [[Beauty Behind the Madness (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Can’t Feel My Face]]
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
		intensity: page["Can’t_Feel_My_Face"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
