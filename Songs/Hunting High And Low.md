---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Hunting High And Low (1985).jpg]]"
---
[Time:: 3:48]
[Artist:: [[a-ha]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 36]
[Album:: [[Hunting High And Low (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hunting High And Low]]
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
		intensity: page["Hunting_High_And_Low"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
