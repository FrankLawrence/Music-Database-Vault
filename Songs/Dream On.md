---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Aerosmith (1976).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Aerosmith]] ]
[Genre:: Rock]
[Played:: 10]
[Album:: [[Aerosmith (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dream On]]
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
		intensity: page["Dream_On"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
