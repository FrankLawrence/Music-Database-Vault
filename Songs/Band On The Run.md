---
tags: Song ⭐⭐ 
banner: "![[All The Best (1973).jpg]]"
---
[Time:: 5:13]
[Artist:: [[Paul McCartney & Wings]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[All The Best (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Band On The Run]]
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
		intensity: page["Band_On_The_Run"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
