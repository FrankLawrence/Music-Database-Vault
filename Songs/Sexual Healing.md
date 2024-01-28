---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Midnight Love (1982).jpg]]"
---
[Time:: 4:05]
[Artist:: [[Marvin Gaye]] ]
[Genre:: Funk]
[Played:: 18]
[Album:: [[Midnight Love (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sexual Healing]]
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
		intensity: page["Sexual_Healing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
