---
tags: Song ⭐⭐⭐⭐ 
banner: "![[The Very Best Of Baccara ().jpg]]"
---
[Time:: 4:35]
[Artist:: [[Baccara]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[The Very Best Of Baccara ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Yes Sir, I can boogie]]
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
		intensity: page["Yes_Sir,_I_can_boogie"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
