---
tags: Song ⭐⭐ 
banner: "![[Time Pieces - The Best Of Eric Clapton (1978).jpg]]"
---
[Time:: 3:00]
[Artist:: [[Eric Clapton]] ]
[Genre:: Blues]
[Played:: ]
[Album:: [[Time Pieces - The Best Of Eric Clapton (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Promises]]
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
		intensity: page["Promises"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
