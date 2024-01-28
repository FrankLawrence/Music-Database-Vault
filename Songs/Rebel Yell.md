---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Rebel Yell (1983).jpg]]"
---
[Time:: 4:47]
[Artist:: [[Billy Idol]] ]
[Genre:: Hard Rock]
[Played:: 5]
[Album:: [[Rebel Yell (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rebel Yell]]
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
		intensity: page["Rebel_Yell"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
