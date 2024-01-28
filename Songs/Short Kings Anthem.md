---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:14]
[Artist:: [[Tiny Meat Gang]] [[Blackbear]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 4]
[Album:: ]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Short Kings Anthem]]
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
		intensity: page["Short_Kings_Anthem"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
