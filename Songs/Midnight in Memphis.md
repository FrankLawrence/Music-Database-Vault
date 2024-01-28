---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Very Best Of J.J. Cale (2005).jpg]]"
---
[Time:: 4:26]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 6]
[Album:: [[The Very Best Of J.J. Cale (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Midnight in Memphis]]
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
		intensity: page["Midnight_in_Memphis"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
