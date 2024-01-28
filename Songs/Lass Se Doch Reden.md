---
tags: Song ⭐ 
banner: "![[Wahnsinn (1995).jpg]]"
---
[Time:: 3:38]
[Artist:: [[BAP]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Wahnsinn (1995)]]]
[Year:: 1995]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lass Se Doch Reden]]
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
		intensity: page["Lass_Se_Doch_Reden"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
