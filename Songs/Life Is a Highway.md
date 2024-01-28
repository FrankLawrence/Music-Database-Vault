---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Me and My Gang (2006).jpg]]"
---
[Time:: 4:29]
[Artist:: [[Rascal Flatts]] ]
[Genre:: Hard Rock]
[Played:: 26]
[Album:: [[Me and My Gang (2006)]]]
[Year:: 2006]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Life Is a Highway]]
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
		intensity: page["Life_Is_a_Highway"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
