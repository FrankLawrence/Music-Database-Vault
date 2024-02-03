---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Balance Of Power (1986).jpg]]"
---
[Time:: 2:44]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Electronic, Rock, Pop]
[Played:: 115]
[Album:: [[Balance Of Power (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[So Serious]]
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
		intensity: page["So_Serious"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
