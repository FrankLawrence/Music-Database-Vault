---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Breakfast In America (1979).jpg]]"
---
[Time:: 4:10]
[Artist:: [[Supertramp]] ]
[Genre:: Rock]
[Played:: 3]
[Album:: [[Breakfast In America (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lord Is It Mine]]
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
		intensity: page["Lord_Is_It_Mine"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
