---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Wall (1979).jpg]]"
---
[Time:: 3:59]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 47]
[Album:: [[The Wall (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Another Brick in the Wall Pt. 2]]
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
		intensity: page["Another_Brick_in_the_Wall_Pt._2"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
