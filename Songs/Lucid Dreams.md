---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Goodbye & Good Riddance (2018).jpg]]"
---
[Time:: 3:50]
[Artist:: [[Juice WRLD]] ]
[Genre:: Hip-Hop/Rap]
[Played:: ]
[Album:: [[Goodbye & Good Riddance (2018)]]]
[Year:: 2018]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Lucid Dreams]]
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
		intensity: page["Lucid_Dreams"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
