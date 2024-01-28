---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Main Course (1975).jpg]]"
---
[Time:: 3:44]
[Artist:: [[Bee Gees]] ]
[Genre:: Pop Rock]
[Played:: 1]
[Album:: [[Main Course (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jive Talkin']]
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
		intensity: page["Jive_Talkin'"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
