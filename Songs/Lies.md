---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Really (1973).jpg]]"
---
[Time:: 2:57]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 4]
[Album:: [[Really (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lies]]
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
		intensity: page["Lies"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
