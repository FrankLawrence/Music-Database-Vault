---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Heartbreaker [UK] (1996).jpg]]"
---
[Time:: 4:11]
[Artist:: [[Pat Benatar]] ]
[Genre:: Rock]
[Played:: 14]
[Album:: [[Heartbreaker [UK] (1996)]]]
[Year:: 1996]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Is A Battlefield]]
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
		intensity: page["Love_Is_A_Battlefield"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
