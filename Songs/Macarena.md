---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A mí me gusta (1993).jpg]]"
---
[Time:: 5:03]
[Artist:: [[Los del Rio]] ]
[Genre:: dance-pop]
[Played:: 2]
[Album:: [[A mí me gusta (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Macarena]]
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
		intensity: page["Macarena"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
