---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[X&Y (2005).jpg]]"
---
[Time:: 4:32]
[Artist:: [[Coldplay]] ]
[Genre:: Rock]
[Played:: 18]
[Album:: [[X&Y (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Twisted Logic]]
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
		intensity: page["Twisted_Logic"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
