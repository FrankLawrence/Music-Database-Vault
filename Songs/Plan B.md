---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Stärker Als Die Zeit (2016).jpg]]"
---
[Time:: 3:46]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: Rock]
[Played:: 14]
[Album:: [[Stärker Als Die Zeit (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Plan B]]
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
		intensity: page["Plan_B"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
