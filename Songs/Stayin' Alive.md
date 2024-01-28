---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Saturday Night Fever (1977).jpg]]"
---
[Time:: 4:43]
[Artist:: [[Bee Gees]] ]
[Genre:: Disco]
[Played:: 15]
[Album:: [[Saturday Night Fever (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Stayin' Alive]]
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
		intensity: page["Stayin'_Alive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
