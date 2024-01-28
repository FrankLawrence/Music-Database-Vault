---
tags: Song ⭐⭐⭐ 
banner: "![[Discovery (2000).jpg]]"
---
[Time:: 5:20]
[Artist:: [[Daft Punk]] ]
[Genre:: French house]
[Played:: 1]
[Album:: [[Discovery (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One More Time]]
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
		intensity: page["One_More_Time"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
