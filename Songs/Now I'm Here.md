---
tags: Song ⭐⭐ 
banner: "![[Sheer Heart Attack (1974).jpg]]"
---
[Time:: 4:15]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[Sheer Heart Attack (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Now I'm Here]]
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
		intensity: page["Now_I'm_Here"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
