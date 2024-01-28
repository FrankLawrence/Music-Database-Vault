---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Very Best Of The Bee Gees (1990).jpg]]"
---
[Time:: 2:49]
[Artist:: [[Bee Gees]] ]
[Genre:: Pop]
[Played:: 5]
[Album:: [[Very Best Of The Bee Gees (1990)]]]
[Year:: 1990]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[First Of May]]
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
		intensity: page["First_Of_May"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
