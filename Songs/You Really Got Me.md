---
tags: Song ⭐⭐⭐ 
banner: "![[Van Halen (1978).jpg]]"
---
[Time:: 2:38]
[Artist:: [[Van Halen]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Van Halen (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Really Got Me]]
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
		intensity: page["You_Really_Got_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
