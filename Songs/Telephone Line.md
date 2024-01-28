---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[A New World Record (1976).jpg]]"
---
[Time:: 4:36]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 14]
[Album:: [[A New World Record (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Telephone Line]]
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
		intensity: page["Telephone_Line"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
