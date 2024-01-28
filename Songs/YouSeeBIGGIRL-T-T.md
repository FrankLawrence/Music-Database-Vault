---
tags: Song ⭐⭐⭐⭐⭐
banner: "![[YouSeeBIGGIRL-T-T.jpg]]"
---
[Time:: 4:08]
[Artist:: [[澤野弘之 (Hiroyuki Sawano)]] ]
[Genre:: Anime]
[Played:: 29]
[Album:: [[Attack on Titan Original Soundtrack (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[YouSeeBIGGIRL-T-T]]
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
		intensity: page["YouSeeBIGGIRL-T-T"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
