---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Night at the Opera (1975).jpg]]"
---
[Time:: 2:51]
[Artist:: [[Queen]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[A Night at the Opera (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You're My Best Friend]]
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
		intensity: page["You're_My_Best_Friend"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
