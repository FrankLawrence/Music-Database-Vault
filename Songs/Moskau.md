---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Die Großen Erfolge ().jpg]]"
---
[Time:: 4:33]
[Artist:: [[Dschinghis Khan]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Die Großen Erfolge ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Moskau]]
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
		intensity: page["Moskau"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
