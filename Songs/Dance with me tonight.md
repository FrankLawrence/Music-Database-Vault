---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:27]
[Artist:: [[Olly Murs]] ]
[Genre:: ]
[Played:: ]
[Album:: ]
[Year:: 2012]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Dance with me tonight]]
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
		intensity: page["Dance_with_me_tonight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
