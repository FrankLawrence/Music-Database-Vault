---
tags: Song  
banner:
---
[Time:: 0:57]
[Artist:: [[]] ]
[Genre:: Instrumental]
[Played:: 3]
[Year:: 2022]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Durk x Drake lol update]]
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
		intensity: page["Durk_x_Drake_lol_update"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
