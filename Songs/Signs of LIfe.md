---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[A Momentary Lapse of Reason (1987).jpg]]"
---
[Time:: 4:24]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 77]
[Album:: [[A Momentary Lapse of Reason (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Signs of Life]]
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
		intensity: page["Signs_of_Life"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
