---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Saturday Night Fever (1977).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Bee Gees]] ]
[Genre:: Disco]
[Played:: 18]
[Album:: [[Saturday Night Fever (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Night Fever]]
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
		intensity: page["Night_Fever"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
