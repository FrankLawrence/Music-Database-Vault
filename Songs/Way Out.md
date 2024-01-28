---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[V I N C E N T (2022).jpg]]"
---
[Time:: 3:20]
[Artist:: [[FKJ]] [[((( O ))]] ]
[Genre:: Electronic]
[Played:: 28]
[Album:: [[V I N C E N T (2022)]]]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Way Out]]
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
		intensity: page["Way_Out"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
