---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Save Me (1975).jpg]]"
---
[Time:: 5:34]
[Artist:: [[Silver Convention]] ]
[Genre:: Euro Disco]
[Played:: 6]
[Album:: [[Save Me (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fly, Robin, Fly]]
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
		intensity: page["Fly,_Robin,_Fly"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
