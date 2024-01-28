---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Abracadabra (1982).jpg]]"
---
[Time:: 3:39]
[Artist:: [[Steve Miller Band]] ]
[Genre:: Rock]
[Played:: 22]
[Album:: [[Abracadabra (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Abracadabra]]
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
		intensity: page["Abracadabra"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
