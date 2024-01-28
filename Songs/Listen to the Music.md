---
tags: Song ⭐⭐⭐ 
banner: "![[Toulouse Street (1972).jpg]]"
---
[Time:: 3:48]
[Artist:: [[The Doobie Brothers]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[Toulouse Street (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Listen to the Music]]
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
		intensity: page["Listen_to_the_Music"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
