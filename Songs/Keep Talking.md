---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[The Division Bell (1994).jpg]]"
---
[Time:: 6:12]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 63]
[Album:: [[The Division Bell (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Keep Talking]]
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
		intensity: page["Keep_Talking"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
