---
tags: Song ⭐ 
banner: "![[Time Pieces - The Best Of Eric Clapton (1975).jpg]]"
---
[Time:: 3:29]
[Artist:: [[Eric Clapton]] ]
[Genre:: Blues]
[Played:: ]
[Album:: [[Time Pieces - The Best Of Eric Clapton (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Swing Low Sweet Chariot]]
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
		intensity: page["Swing_Low_Sweet_Chariot"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
