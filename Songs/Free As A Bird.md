---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Free As A Bird (1987).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 36]
[Album:: [[Free As A Bird (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Free As A Bird]]
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
		intensity: page["Free_As_A_Bird"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
