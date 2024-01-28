---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:55]
[Artist:: [[Maître Gims]] ]
[Genre:: Rock Pop]
[Played:: ]
[Played:: 1]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Est-ce que tu maimes]]
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
		intensity: page["Est-ce_que_tu_maimes"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
