---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[West Ryder Pauper Lunatic Asylum (2009).jpg]]"
---
[Time:: 4:12]
[Artist:: [[Kasabian]] ]
[Genre:: Psychedelic Rock]
[Played:: 16]
[Album:: [[West Ryder Pauper Lunatic Asylum (2009)]]]
[Year:: 2009]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fire]]
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
		intensity: page["Fire"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
