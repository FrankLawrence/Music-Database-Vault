---
tags: Song ⭐⭐⭐⭐⭐ 💛

[Time:: 9:17]
[Artist:: [[Ewan Dobson]] ]
[Genre:: Acoustic guitar]
[Played:: 10]
[Played:: 2]
[Year:: 2010]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Blood and Ice]]
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
		intensity: page["Blood_and_Ice"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
