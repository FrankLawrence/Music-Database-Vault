---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Endless Love (1981).jpg]]"
---
[Time:: 4:28]
[Artist:: [[Lionel Richie & Diana Ross]] ]
[Genre:: R&B]
[Played:: 5]
[Album:: [[Endless Love (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Endless Love]]
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
		intensity: page["Endless_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
