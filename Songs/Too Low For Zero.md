---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Too Low For Zero (1983).jpg]]"
---
[Time:: 5:46]
[Artist:: [[Elton John]] ]
[Genre:: Pop Rock]
[Played:: ]
[Album:: [[Too Low For Zero (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Too Low For Zero]]
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
		intensity: page["Too_Low_For_Zero"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
