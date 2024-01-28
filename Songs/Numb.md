---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Meteora (2003).jpg]]"
---
[Time:: 3:06]
[Artist:: [[Linkin Park]] ]
[Genre:: Alternative Rock]
[Played:: 22]
[Album:: [[Meteora (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Numb]]
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
		intensity: page["Numb"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
