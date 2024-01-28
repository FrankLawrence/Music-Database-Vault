---
tags: Song ⭐⭐⭐ 
banner: "![[AM (2013).jpg]]"
---
[Time:: 2:44]
[Artist:: [[Arctic Monkeys]] ]
[Genre:: Funk rock]
[Played:: 1]
[Album:: [[AM (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Why'd You Only Call Me When You're High?]]
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
		intensity: page["Why'd_You_Only_Call_Me_When_You're_High?"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
