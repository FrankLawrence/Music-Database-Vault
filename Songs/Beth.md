---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Kiss (1976).jpg]]"
---
[Time:: 2:48]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Greatest Kiss (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Beth]]
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
		intensity: page["Beth"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
