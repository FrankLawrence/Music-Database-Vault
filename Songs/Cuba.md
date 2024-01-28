---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Pure Disco (1979).jpg]]"
---
[Time:: 3:41]
[Artist:: [[Gibson Brothers]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Pure Disco (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cuba]]
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
		intensity: page["Cuba"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
