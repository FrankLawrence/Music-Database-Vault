---
tags: Song ⭐ 💔
banner: "![[Between the Buttons (2007).jpg]]"
---
[Time:: 2:05]
[Artist:: [[The Rolling Stones]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Between the Buttons (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Yesterday's Papers]]
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
		intensity: page["Yesterday's_Papers"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
