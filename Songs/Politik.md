---
tags: Song ⭐⭐⭐⭐ 
banner: "![[A Rush of Blood To The Head ().jpg]]"
---
[Time:: 5:19]
[Artist:: [[Coldplay]] ]
[Genre:: Soul]
[Played:: 8]
[Album:: [[A Rush of Blood To The Head ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Politik]]
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
		intensity: page["Politik"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
