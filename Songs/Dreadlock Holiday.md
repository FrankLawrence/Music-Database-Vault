---
tags: Song ⭐⭐⭐ 
banner: "![[Bloody Tourists (1978).jpg]]"
---
[Time:: 4:14]
[Artist:: [[10cc]] ]
[Genre:: Cod Reggae]
[Played:: 3]
[Album:: [[Bloody Tourists (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dreadlock Holiday]]
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
		intensity: page["Dreadlock_Holiday"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
