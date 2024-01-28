---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Deepest Purple: The Very Best Of ... (1972).jpg]]"
---
[Time:: 5:40]
[Artist:: [[Deep Purple]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Deepest Purple: The Very Best Of ... (1972)]]]
[Year:: 1972]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Smoke On The Water]]
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
		intensity: page["Smoke_On_The_Water"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
