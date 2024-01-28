---
tags: Song ⭐⭐⭐⭐ 

[Time:: 3:29]
[Artist:: [[Mark Forster]] ]
[Genre:: ]
[Played:: ]
[Played:: 1]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Chöre (Willkommen bei den Hartmanns Version)]]
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
		intensity: page["Chöre_(Willkommen_bei_den_Hartmanns_Version)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
