---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Saturday Night Fever (1977).jpg]]"
---
[Time:: 3:16]
[Artist:: [[Bee Gees]] ]
[Genre:: Disco]
[Played:: 16]
[Album:: [[Saturday Night Fever (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[More Than A Woman]]
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
		intensity: page["More_Than_A_Woman"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
