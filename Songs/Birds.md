---
tags: Song ⭐⭐⭐ 
banner: "![[A Head Full Of Dreams (2015).jpg]]"
---
[Time:: 3:49]
[Artist:: [[Coldplay]] ]
[Genre:: Rock, Pop]
[Played:: 2]
[Album:: [[A Head Full Of Dreams (2015)]]]
[Year:: 2015]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Birds]]
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
		intensity: page["Birds"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
