---
tags: Song ⭐⭐⭐ 
banner: "![[Greatest Hits - Das Beste (1970).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Les Humphries Singers]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Greatest Hits - Das Beste (1970)]]]
[Year:: 1970]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Do You Wanna Rock And Roll?]]
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
		intensity: page["Do_You_Wanna_Rock_And_Roll?"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
