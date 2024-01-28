---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1956).jpg]]"
---
[Time:: 2:45]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[30 #1 Hits (1956)]]]
[Year:: 1956]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Me Tender]]
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
		intensity: page["Love_Me_Tender"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
