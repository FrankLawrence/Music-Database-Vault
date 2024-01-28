---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Music from the Edge of Heaven (2006).jpg]]"
---
[Time:: 4:03]
[Artist:: [[George Michael]] ]
[Genre:: Pop]
[Played:: 48]
[Album:: [[Music from the Edge of Heaven (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Different Corner]]
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
		intensity: page["A_Different_Corner"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
