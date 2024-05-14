---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Attack on Titan Original Soundtrack ().jpg]]"
---
[Time:: 1:30]
[Artist:: [[Linked Horizon]] ]
[Genre:: Anime]
[Played:: 21]
[Album:: [[Attack on Titan Original Soundtrack ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shoukei to Shikabane no Michi (TV Size)]]
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
		intensity: page["Shoukei_to_Shikabane_no_Michi_(TV_Size)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
