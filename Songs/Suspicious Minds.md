---
tags: Song ⭐⭐⭐ 
banner: "![[30 #1 Hits (1967).jpg]]"
---
[Time:: 4:35]
[Artist:: [[Elvis Presley]] ]
[Genre:: Rock]
[Played:: 2]
[Album:: [[30 #1 Hits (1967)]]]
[Year:: 1967]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Suspicious Minds]]
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
		intensity: page["Suspicious_Minds"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
