---
tags: Song ⭐⭐⭐ 
banner: "![[7 (2018).jpg]]"
---
[Time:: 3:23]
[Artist:: [[David Guetta]] [[Martin Garrix & Brooks]] ]
[Genre:: EDM]
[Played:: 1]
[Album:: [[7 (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Like I Do]]
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
		intensity: page["Like_I_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
