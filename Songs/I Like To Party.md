---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:05]
[Artist:: [[Jagwar Twin]] ]
[Genre:: Alternative]
[Played:: 9]
[Played:: 1]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Like To Party]]
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
		intensity: page["I_Like_To_Party"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
