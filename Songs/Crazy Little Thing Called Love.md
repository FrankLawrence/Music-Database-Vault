---
tags: Song ⭐⭐⭐ 
banner: "![[The Game (1977).jpg]]"
---
[Time:: 2:44]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[The Game (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Crazy Little Thing Called Love]]
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
		intensity: page["Crazy_Little_Thing_Called_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
