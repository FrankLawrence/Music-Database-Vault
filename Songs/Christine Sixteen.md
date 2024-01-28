---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Kiss (1977).jpg]]"
---
[Time:: 3:15]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Greatest Kiss (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Christine Sixteen]]
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
		intensity: page["Christine_Sixteen"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
