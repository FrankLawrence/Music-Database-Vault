---
tags: Song ⭐⭐⭐ 
banner: "![[The Final Cut (1983).jpg]]"
---
[Time:: 2:43]
[Artist:: [[Pink Floyd]] ]
[Genre:: Art rock]
[Played:: 6]
[Album:: [[The Final Cut (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Hero's return]]
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
		intensity: page["The_Hero's_return"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
