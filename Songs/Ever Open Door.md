---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Brother Where You Bound (1985).jpg]]"
---
[Time:: 3:04]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 2]
[Album:: [[Brother Where You Bound (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ever Open Door]]
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
		intensity: page["Ever_Open_Door"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
