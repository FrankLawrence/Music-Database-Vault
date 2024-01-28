---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Bobby Caldwell (1978).jpg]]"
---
[Time:: 4:44]
[Artist:: [[Bobby Caldwell]] ]
[Genre:: Jazz]
[Played:: 36]
[Album:: [[Bobby Caldwell (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What You Won't Do for Love]]
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
		intensity: page["What_You_Won't_Do_for_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
