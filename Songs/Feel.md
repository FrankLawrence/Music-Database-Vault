---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Escapology (2002).jpg]]"
---
[Time:: 4:24]
[Artist:: [[Robbie Williams]] ]
[Genre:: Pop]
[Played:: 6]
[Album:: [[Escapology (2002)]]]
[Year:: 2002]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Feel]]
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
		intensity: page["Feel"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
