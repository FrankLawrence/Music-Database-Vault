---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Time Pieces - The Best Of Eric Clapton (1977).jpg]]"
---
[Time:: 3:39]
[Artist:: [[Eric Clapton]] ]
[Genre:: Blues]
[Played:: ]
[Album:: [[Time Pieces - The Best Of Eric Clapton (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wonderful Tonight]]
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
		intensity: page["Wonderful_Tonight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
