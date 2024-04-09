---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Part 3 (1976).jpg]]"
---
[Time:: 3:08]
[Artist:: [[K.C. & The Sunshine Band]] ]
[Genre:: Disco]
[Played:: 8]
[Album:: [[Part 3 (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shake Your Booty]]
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
		intensity: page["Shake_Your_Booty"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
