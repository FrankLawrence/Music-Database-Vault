---
tags: Song ⭐⭐⭐ 
banner: "![[Animals (1977).jpg]]"
---
[Time:: 1:29]
[Artist:: [[Pink Floyd]] ]
[Genre:: Progressive Rock]
[Played:: 3]
[Album:: [[Animals (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Pigs On The Wing (Part Two)]]
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
		intensity: page["Pigs_On_The_Wing_(Part_Two)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
