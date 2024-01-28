---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Dead Letters (2003).jpg]]"
---
[Time:: 3:52]
[Artist:: [[The Rasmus]] ]
[Genre:: Alternative Rock]
[Played:: 9]
[Album:: [[Dead Letters (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[In The Shadows]]
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
		intensity: page["In_The_Shadows"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
