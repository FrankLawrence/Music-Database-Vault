---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Californication (2000).jpg]]"
---
[Time:: 5:21]
[Artist:: [[Red Hot Chili Peppers]] ]
[Genre:: Alternative Rock]
[Played:: 2]
[Album:: [[Californication (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Californication]]
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
		intensity: page["Californication"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
