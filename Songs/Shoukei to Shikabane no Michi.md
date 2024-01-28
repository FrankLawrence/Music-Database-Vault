---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Attack on Titan Original Soundtrack ().jpg]]"
---
[Time:: 4:35]
[Artist:: [[Linked Horizon]] ]
[Genre:: J-Pop]
[Played:: 7]
[Album:: [[Attack on Titan Original Soundtrack ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shoukei to Shikabane no Michi]]
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
		intensity: page["Shoukei_to_Shikabane_no_Michi"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
