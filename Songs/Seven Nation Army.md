---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Elephant (2003).jpg]]"
---
[Time:: 3:58]
[Artist:: [[The White Stripes]] ]
[Genre:: Alternative Rock]
[Played:: 1]
[Album:: [[Elephant (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Seven Nation Army]]
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
		intensity: page["Seven_Nation_Army"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
