---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Search (2019).jpg]]"
---
[Time:: 4:01]
[Artist:: [[NF]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 20]
[Album:: [[The Search (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[When I Grow Up]]
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
		intensity: page["When_I_Grow_Up"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
