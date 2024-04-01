---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Torches (2011).jpg]]"
---
[Time:: 3:00]
[Artist:: [[Foster the People]] ]
[Genre:: Psychedelic Pop]
[Played:: 23]
[Album:: [[Torches (2011)]]]
[Year:: 2011]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Stop (Color on the Walls)]]
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
		intensity: page["Don't_Stop_(Color_on_the_Walls)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
