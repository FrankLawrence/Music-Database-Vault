---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Black Holes and Revelations (2006).jpg]]"
---
[Time:: 3:31]
[Artist:: [[Muse]] ]
[Genre:: Alternative Rock]
[Played:: 32]
[Album:: [[Black Holes and Revelations (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Supermassive Black Hole]]
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
		intensity: page["Supermassive_Black_Hole"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
