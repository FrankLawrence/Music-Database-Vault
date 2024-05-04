---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Parachutes (2000).jpg]]"
---
[Time:: 4:17]
[Artist:: [[Coldplay]] ]
[Genre:: Alternative Rock]
[Played:: 47]
[Album:: [[Parachutes (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[High Speed]]
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
		intensity: page["High_Speed"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
