---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Captain and Me (1973).jpg]]"
---
[Time:: 3:42]
[Artist:: [[The Doobie Brothers]] ]
[Genre:: Country Rock]
[Played:: 9]
[Album:: [[The Captain and Me (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Long Train Running]]
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
		intensity: page["Long_Train_Running"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
