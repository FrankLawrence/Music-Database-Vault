---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1957).jpg]]"
---
[Time:: 1:49]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[30 #1 Hits (1957)]]]
[Year:: 1957]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(Let Me Be Your) Teddy Bear]]
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
		intensity: page["(Let_Me_Be_Your)_Teddy_Bear"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
