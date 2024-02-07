---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Jump (1984).jpg]]"
---
[Time:: 4:04]
[Artist:: [[Van Halen]] ]
[Genre:: Rock]
[Played:: 20]
[Album:: [[Jump (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jump]]
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
		intensity: page["Jump"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
