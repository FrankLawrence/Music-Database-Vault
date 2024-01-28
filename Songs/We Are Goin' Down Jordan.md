---
tags: Song  
banner: "![[Greatest Hits - Das Beste (1970).jpg]]"
---
[Time:: 3:01]
[Artist:: [[Les Humphries Singers]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Greatest Hits - Das Beste (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We Are Goin' Down Jordan]]
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
		intensity: page["We_Are_Goin'_Down_Jordan"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
