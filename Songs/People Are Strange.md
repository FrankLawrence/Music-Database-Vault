---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Strange Days (1967).jpg]]"
---
[Time:: 2:10]
[Artist:: [[The Doors]] ]
[Genre:: Pop]
[Played:: 20]
[Album:: [[Strange Days (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[People Are Strange]]
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
		intensity: page["People_Are_Strange"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
