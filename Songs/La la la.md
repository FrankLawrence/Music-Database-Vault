---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Hotel Cabana (2013).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Naughty Boy]] [[Sam Smith]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Hotel Cabana (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[La la la]]
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
		intensity: page["La_la_la"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
