---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Kaleidoscope (2017).jpg]]"
---
[Time:: 5:54]
[Artist:: [[Coldplay]] ]
[Genre:: Soft Rock]
[Played:: 16]
[Album:: [[Kaleidoscope (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hypnotised]]
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
		intensity: page["Hypnotised"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
