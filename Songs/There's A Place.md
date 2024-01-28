---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Please Please Me (1963).jpg]]"
---
[Time:: 1:53]
[Artist:: [[The Beatles]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Please Please Me (1963)]]]
[Year:: 1963]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[There's A Place]]
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
		intensity: page["There's_A_Place"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
