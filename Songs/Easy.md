---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Commodores (1977).jpg]]"
---
[Time:: 4:17]
[Artist:: [[Lionel Richie]] ]
[Genre:: Soul]
[Played:: 1]
[Album:: [[Commodores (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Easy]]
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
		intensity: page["Easy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
