---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Parachutes (2000).jpg]]"
---
[Time:: 4:34]
[Artist:: [[Coldplay]] ]
[Genre:: Alternative Rock]
[Played:: 60]
[Album:: [[Parachutes (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Trouble]]
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
		intensity: page["Trouble"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
