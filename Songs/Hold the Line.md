---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Toto (1978).jpg]]"
---
[Time:: 3:58]
[Artist:: [[Toto]] ]
[Genre:: Hard Rock]
[Played:: 37]
[Album:: [[Toto (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hold the Line]]
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
		intensity: page["Hold_the_Line"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
