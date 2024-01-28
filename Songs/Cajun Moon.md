---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Okie (1974).jpg]]"
---
[Time:: 2:16]
[Artist:: [[J.J. Cale]] ]
[Genre:: Blues]
[Played:: 11]
[Album:: [[Okie (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cajun Moon]]
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
		intensity: page["Cajun_Moon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
