---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Children of the World (1967).jpg]]"
---
[Time:: 4:47]
[Artist:: [[Bee Gees]] ]
[Genre:: Disco]
[Played:: 11]
[Album:: [[Children of the World (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[You Should Be Dancing]]
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
		intensity: page["You_Should_Be_Dancing"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
