---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Reload (1998).jpg]]"
---
[Time:: 6:36]
[Artist:: [[Metallica]] ]
[Genre:: Heavy metal]
[Played:: 4]
[Album:: [[Reload (1998)]]]
[Year:: 1998]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Unforgiven (II)]]
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
		intensity: page["Unforgiven_(II)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
