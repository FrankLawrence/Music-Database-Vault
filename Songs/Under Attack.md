---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[The Visitors (1981).jpg]]"
---
[Time:: 3:44]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 75]
[Album:: [[The Visitors (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Under Attack]]
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
		intensity: page["Under_Attack"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
