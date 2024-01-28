---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Discovery (1990).jpg]]"
---
[Time:: 4:42]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 11]
[Album:: [[Discovery (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shine A Little Love]]
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
		intensity: page["Shine_A_Little_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
