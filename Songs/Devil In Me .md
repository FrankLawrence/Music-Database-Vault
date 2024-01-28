---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 3:17]
[Artist:: [[Purple Disco Machine]] [[Joe Killington & Duane Harden]] ]
[Genre:: Rock/Pop]
[Played:: 5]
[Album:: ]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Devil In Me ]]
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
		intensity: page["Devil_In_Me_"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
