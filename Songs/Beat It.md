---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Thriller (1982).jpg]]"
---
[Time:: 4:58]
[Artist:: [[Michael Jackson]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Thriller (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Beat It]]
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
		intensity: page["Beat_It"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
