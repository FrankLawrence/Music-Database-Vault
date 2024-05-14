---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Parachutes (2000).jpg]]"
---
[Time:: 2:17]
[Artist:: [[Coldplay]] ]
[Genre:: Soft Rock]
[Played:: 16]
[Album:: [[Parachutes (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Panic]]
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
		intensity: page["Don't_Panic"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
