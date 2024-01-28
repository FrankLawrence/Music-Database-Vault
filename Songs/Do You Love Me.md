---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Kiss (1976).jpg]]"
---
[Time:: 3:34]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Greatest Kiss (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Do You Love Me]]
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
		intensity: page["Do_You_Love_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
