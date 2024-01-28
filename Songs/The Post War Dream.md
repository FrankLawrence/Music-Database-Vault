---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Final Cut (1983).jpg]]"
---
[Time:: 3:01]
[Artist:: [[Pink Floyd]] ]
[Genre:: Art rock]
[Played:: 32]
[Album:: [[The Final Cut (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Post War Dream]]
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
		intensity: page["The_Post_War_Dream"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
