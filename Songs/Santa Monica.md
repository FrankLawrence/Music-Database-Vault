---
tags: Song ⭐⭐⭐⭐ 
banner: "![[WELCOME HOME (2019).jpg]]"
---
[Time:: 2:53]
[Artist:: [[Aries]] ]
[Genre:: Hip-Hop/Rap]
[Played:: ]
[Album:: [[WELCOME HOME (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Santa Monica]]
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
		intensity: page["Santa_Monica"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
