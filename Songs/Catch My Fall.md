---
tags: Song ⭐⭐⭐ 
banner: "![[Vital Idol (1987).jpg]]"
---
[Time:: 4:58]
[Artist:: [[Billy Idol]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[Vital Idol (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Catch My Fall]]
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
		intensity: page["Catch_My_Fall"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
