---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:49]
[Artist:: [[Calvin Harris RagnBone Man]] ]
[Genre:: Rock Pop]
[Played:: 3]
[Played:: 1]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Giant]]
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
		intensity: page["Giant"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
