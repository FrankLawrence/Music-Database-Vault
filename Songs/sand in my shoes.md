---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Sand in my Shoes (2003).jpg]]"
---
[Time:: 4:59]
[Artist:: [[Dido]] ]
[Genre:: Pop]
[Played:: 18]
[Album:: [[Sand in my Shoes (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[sand in my shoes]]
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
		intensity: page["sand_in_my_shoes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
