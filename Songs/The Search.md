---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Search (2019).jpg]]"
---
[Time:: 4:52]
[Artist:: [[NF]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 16]
[Album:: [[The Search (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[The Search]]
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
		intensity: page["The_Search"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
