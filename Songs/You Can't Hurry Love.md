---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Hello, I Must Be Going! (1982).jpg]]"
---
[Time:: 2:56]
[Artist:: [[Phil Collins]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Hello, I Must Be Going! (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Can't Hurry Love]]
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
		intensity: page["You_Can't_Hurry_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
