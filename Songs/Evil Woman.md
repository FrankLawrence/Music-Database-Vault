---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Face the Music (1975).jpg]]"
---
[Time:: 4:12]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 8]
[Album:: [[Face the Music (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Evil Woman]]
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
		intensity: page["Evil_Woman"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
