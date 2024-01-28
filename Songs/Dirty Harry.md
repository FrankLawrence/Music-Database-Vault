---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Demon Days (2005).jpg]]"
---
[Time:: 3:44]
[Artist:: [[Gorillaz ft.Bootie Brown]] ]
[Genre:: Funk]
[Played:: 12]
[Album:: [[Demon Days (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dirty Harry]]
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
		intensity: page["Dirty_Harry"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
