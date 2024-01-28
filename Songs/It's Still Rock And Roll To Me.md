---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Piano Man (1980).jpg]]"
---
[Time:: 2:57]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 8]
[Album:: [[Piano Man (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[It's Still Rock And Roll To Me]]
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
		intensity: page["It's_Still_Rock_And_Roll_To_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
