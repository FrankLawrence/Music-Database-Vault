---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Discovery (1979).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 16]
[Album:: [[Discovery (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Bring Me Down]]
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
		intensity: page["Don't_Bring_Me_Down"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
