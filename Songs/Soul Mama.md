---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:34]
[Artist:: [[Zucchero]] ]
[Genre:: Disco]
[Played:: 3]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Soul Mama]]
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
		intensity: page["Soul_Mama"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
