---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Their Greatest Hits (1978).jpg]]"
---
[Time:: 4:02]
[Artist:: [[Hot Chocolate]] ]
[Genre:: Pop]
[Played:: 12]
[Album:: [[Their Greatest Hits (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Every 1's A Winner]]
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
		intensity: page["Every_1's_A_Winner"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
