---
tags: Song ⭐⭐⭐⭐ 

[Time:: 5:05]
[Artist:: [[Mick Gordon]] ]
[Genre:: Instrumental]
[Played:: 1]
[Played:: 2]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Only Thing They Fear Is You]]
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
		intensity: page["The_Only_Thing_They_Fear_Is_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
