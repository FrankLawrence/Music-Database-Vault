---
tags: Song ⭐⭐⭐ 
banner: "![[Twenty Five (2006).jpg]]"
---
[Time:: 5:49]
[Artist:: [[George Michael]] [[Elton John]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Twentyfive (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Let The Sun Go Down On Me]]
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
		intensity: page["Don't_Let_The_Sun_Go_Down_On_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
