---
tags: Song  
banner: "![[Crime of the Century (1974).jpg]]"
---
[Time:: 5:33]
[Artist:: [[Supertramp]] ]
[Genre:: Progressive Rock]
[Played:: 7]
[Album:: [[Crime of the Century (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Crime Of The Century]]
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
		intensity: page["Crime_Of_The_Century"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
