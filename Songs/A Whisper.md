---
tags: Song ⭐⭐⭐ 
banner: "![[A Rush of Blood To The Head ().jpg]]"
---
[Time:: 3:57]
[Artist:: [[Coldplay]] ]
[Genre:: Soul]
[Played:: 3]
[Album:: [[A Rush of Blood To The Head ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[A Whisper]]
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
		intensity: page["A_Whisper"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
