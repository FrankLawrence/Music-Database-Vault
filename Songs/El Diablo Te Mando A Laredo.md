---
tags: Song ⭐⭐⭐ 
banner: "![[The Very Best Of Baccara ().jpg]]"
---
[Time:: 3:53]
[Artist:: [[Baccara]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[The Very Best Of Baccara ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[El Diablo Te Mando A Laredo]]
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
		intensity: page["El_Diablo_Te_Mando_A_Laredo"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
