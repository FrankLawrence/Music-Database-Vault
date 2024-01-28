---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Attack on Titan Original Soundtrack ().jpg]]"
---
[Time:: 1:29]
[Artist:: [[Linked Horizon]] ]
[Genre:: Anime]
[Played:: 17]
[Album:: [[Attack on Titan Original Soundtrack ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jiyū no Tsubasa (TV Size)]]
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
		intensity: page["Jiyū_no_Tsubasa_(TV_Size)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
