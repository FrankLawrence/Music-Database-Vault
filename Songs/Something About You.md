---
tags: Song ⭐⭐⭐⭐ 
banner: "![[World Machine (1985).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Level 42]] ]
[Genre:: New Wave]
[Played:: 3]
[Album:: [[World Machine (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Something About You]]
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
		intensity: page["Something_About_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
