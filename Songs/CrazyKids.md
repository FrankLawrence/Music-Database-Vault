---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Crazy Kids (2013).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Kesha]] ]
[Genre:: ]
[Played:: 2]
[Album:: [[Crazy Kids (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[CrazyKids]]
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
		intensity: page["CrazyKids"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
