---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Boston (1976).jpg]]"
---
[Time:: 4:45]
[Artist:: [[Boston]] ]
[Genre:: Hard Rock]
[Played:: ]
[Album:: [[Boston (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[More Than a Feeling]]
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
		intensity: page["More_Than_a_Feeling"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
