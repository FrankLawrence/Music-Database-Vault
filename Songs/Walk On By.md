---
tags: Song ⭐⭐ 
banner: "![[The Very Best Of Smooth Jazz [Disc 1] (1968).jpg]]"
---
[Time:: 3:22]
[Artist:: [[George Benson]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[The Very Best Of Smooth Jazz [Disc 1] (1968)]]]
[Year:: 1968]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Walk On By]]
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
		intensity: page["Walk_On_By"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
