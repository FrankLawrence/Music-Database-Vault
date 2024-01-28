---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Player (1977).jpg]]"
---
[Time:: 3:56]
[Artist:: [[Player]] ]
[Genre:: Soft Rock]
[Played:: 20]
[Album:: [[Player (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Baby Come Back]]
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
		intensity: page["Baby_Come_Back"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
