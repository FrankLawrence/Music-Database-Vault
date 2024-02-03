---
tags: Song ⭐⭐⭐ 
banner: "![[Free As A Bird (1987).jpg]]"
---
[Time:: 4:17]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 37]
[Album:: [[Free As A Bird (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Never Can Tell With Friends]]
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
		intensity: page["You_Never_Can_Tell_With_Friends"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
