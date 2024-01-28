---
tags: Song ⭐⭐⭐ 
banner: "![[Piano Man (1993).jpg]]"
---
[Time:: 4:19]
[Artist:: [[Billy Joel]] ]
[Genre:: Pop]
[Played:: 3]
[Album:: [[Piano Man (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All About Soul]]
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
		intensity: page["All_About_Soul"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
