---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Please Please Me (1963).jpg]]"
---
[Time:: 2:56]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Please Please Me (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Saw Her Standing There]]
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
		intensity: page["I_Saw_Her_Standing_There"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
