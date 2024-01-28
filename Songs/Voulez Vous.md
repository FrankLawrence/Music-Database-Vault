---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Voulez-vous (1979).jpg]]"
---
[Time:: 4:23]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Voulez-vous (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Voulez Vous]]
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
		intensity: page["Voulez_Vous"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
