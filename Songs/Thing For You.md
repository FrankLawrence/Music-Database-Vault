---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Free As A Bird (1987).jpg]]"
---
[Time:: 4:00]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 21]
[Album:: [[Free As A Bird (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Thing For You]]
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
		intensity: page["Thing_For_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
