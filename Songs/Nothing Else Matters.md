---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Metallica (1997).jpg]]"
---
[Time:: 6:26]
[Artist:: [[Metallica]] ]
[Genre:: Hard Rock]
[Played:: 8]
[Album:: [[Metallica (1997)]]]
[Year:: 1997]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Nothing Else Matters]]
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
		intensity: page["Nothing_Else_Matters"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
