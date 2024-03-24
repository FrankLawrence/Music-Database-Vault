---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Out Of The Blue (1977).jpg]]"
---
[Time:: 3:47]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Rock]
[Played:: 108]
[Album:: [[Out Of The Blue (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Turn To Stone]]
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
		intensity: page["Turn_To_Stone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
