---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Spirits Having Flown (1979).jpg]]"
---
[Time:: 5:04]
[Artist:: [[Bee Gees]] ]
[Genre:: Disco]
[Played:: 12]
[Album:: [[Spirits Having Flown (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Tragedy]]
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
		intensity: page["Tragedy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
