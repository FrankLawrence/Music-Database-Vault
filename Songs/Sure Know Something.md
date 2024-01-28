---
tags: Song ⭐⭐⭐ 
banner: "![[Greatest Kiss (1979).jpg]]"
---
[Time:: 4:02]
[Artist:: [[Kiss]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Greatest Kiss (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sure Know Something]]
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
		intensity: page["Sure_Know_Something"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
