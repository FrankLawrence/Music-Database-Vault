---
tags: Song ⭐⭐ 
banner: "![[X&Y (2005).jpg]]"
---
[Time:: 3:59]
[Artist:: [[Coldplay]] ]
[Genre:: Space Rock]
[Played:: 4]
[Album:: [[X&Y (2005)]]]
[Year:: 2005]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Swallowed in the Sea]]
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
		intensity: page["Swallowed_in_the_Sea"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
