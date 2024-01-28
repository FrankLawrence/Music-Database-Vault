---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Mellow Gold (1992).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Beck]] ]
[Genre:: Alternative Rock]
[Played:: 7]
[Album:: [[Mellow Gold (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Loser]]
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
		intensity: page["Loser"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
