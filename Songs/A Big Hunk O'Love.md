---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1959).jpg]]"
---
[Time:: 2:17]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[30 #1 Hits (1959)]]]
[Year:: 1959]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Big Hunk O'Love]]
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
		intensity: page["A_Big_Hunk_O'Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
