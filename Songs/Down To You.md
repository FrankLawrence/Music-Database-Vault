---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:52]
[Artist:: [[Jagwar Twin]] ]
[Genre:: Alternative Rock]
[Played:: 14]
[Album:: ]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Down To You]]
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
		intensity: page["Down_To_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
