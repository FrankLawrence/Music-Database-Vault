---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Faith (1987).jpg]]"
---
[Time:: 3:16]
[Artist:: [[George Michael]] ]
[Genre:: Blue-eyed soul]
[Played:: ]
[Album:: [[Faith (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Faith]]
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
		intensity: page["Faith"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
