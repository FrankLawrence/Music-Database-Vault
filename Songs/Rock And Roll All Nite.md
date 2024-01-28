---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Greatest Kiss (1975).jpg]]"
---
[Time:: 2:49]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[Greatest Kiss (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rock And Roll All Nite]]
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
		intensity: page["Rock_And_Roll_All_Nite"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
