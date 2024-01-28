---
tags: Song ⭐⭐⭐ 
banner: "![[Wish You Were Here (1973).jpg]]"
---
[Time:: 7:29]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 12]
[Album:: [[Wish You Were Here (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Welcome to the Machine]]
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
		intensity: page["Welcome_to_the_Machine"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
