---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Hybrid Theory (2001).jpg]]"
---
[Time:: 3:13]
[Artist:: [[Linkin Park]] ]
[Genre:: Rap Metal]
[Played:: 46]
[Album:: [[Hybrid Theory (2001)]]]
[Year:: 2001]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Papercut]]
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
		intensity: page["Papercut"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
