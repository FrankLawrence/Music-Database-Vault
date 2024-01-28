---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Origins (2018).jpg]]"
---
[Time:: 4:44]
[Artist:: [[Imagine Dragons]] ]
[Genre:: Electropop]
[Played:: 1]
[Album:: [[Origins (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Bad Liar]]
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
		intensity: page["Bad_Liar"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
