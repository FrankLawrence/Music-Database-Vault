---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Can't Get Enough (1975).jpg]]"
---
[Time:: 4:35]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 8]
[Album:: [[Can't Get Enough (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You're The First, The Last, My Everything]]
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
		intensity: page["You're_The_First,_The_Last,_My_Everything"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
