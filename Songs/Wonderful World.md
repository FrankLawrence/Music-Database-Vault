---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Best of Herman and the Hermits (1965).jpg]]"
---
[Time:: 2:02]
[Artist:: [[Herman's Hermits]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[The Best of Herman and the Hermits (1965)]]]
[Year:: 1965]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wonderful World]]
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
		intensity: page["Wonderful_World"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
