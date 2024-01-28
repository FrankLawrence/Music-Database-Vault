---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Brothers in Arms (1985).jpg]]"
---
[Time:: 8:22]
[Artist:: [[Dire Straits]] ]
[Genre:: Pop Rock]
[Played:: 5]
[Album:: [[Brothers in Arms (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Money for Nothing]]
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
		intensity: page["Money_for_Nothing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
