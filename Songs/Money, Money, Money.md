---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Arrival (1976).jpg]]"
---
[Time:: 3:08]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 30]
[Album:: [[Arrival (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Money, Money, Money]]
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
		intensity: page["Money,_Money,_Money"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
