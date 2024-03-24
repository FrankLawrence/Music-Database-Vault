---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Wall (1979).jpg]]"
---
[Time:: 1:17]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 44]
[Album:: [[The Wall (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Goodbye Cruel World]]
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
		intensity: page["Goodbye_Cruel_World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
