---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Life for rent (2003).jpg]]"
---
[Time:: 10:36]
[Artist:: [[Dido]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Life for rent (2003)]]]
[Year:: 2003]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[see the sun]]
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
		intensity: page["see_the_sun"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
