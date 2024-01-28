---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Kiss (1979).jpg]]"
---
[Time:: 4:31]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Greatest Kiss (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Was Made For Lovin' You]]
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
		intensity: page["I_Was_Made_For_Lovin'_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
