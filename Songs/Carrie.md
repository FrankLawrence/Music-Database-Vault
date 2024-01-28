---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[The Final Countdown (1987).jpg]]"
---
[Time:: 4:31]
[Artist:: [[Europe]] ]
[Genre:: Glam metal]
[Played:: 16]
[Album:: [[The Final Countdown (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Carrie]]
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
		intensity: page["Carrie"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
