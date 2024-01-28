---
tags: Song ⭐⭐⭐⭐ 
banner: "![[This Is Acting (2016).jpg]]"
---
[Time:: 3:40]
[Artist:: [[Sia]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[This Is Acting (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Unstoppable]]
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
		intensity: page["Unstoppable"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
