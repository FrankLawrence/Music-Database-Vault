---
tags: Song ⭐ 
banner: "![[Wahnsinn (1981).jpg]]"
---
[Time:: 5:49]
[Artist:: [[BAP]] ]
[Genre:: German Rock-Pop]
[Played:: 4]
[Album:: [[Wahnsinn (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Verdamp Lang Her]]
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
		intensity: page["Verdamp_Lang_Her"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
