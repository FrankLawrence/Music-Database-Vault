---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Confessions on a Dance Floor (2005).jpg]]"
---
[Time:: 5:36]
[Artist:: [[Madonna]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Confessions on a Dance Floor (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hung up]]
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
		intensity: page["Hung_up"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
