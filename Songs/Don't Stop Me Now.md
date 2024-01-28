---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Jazz (1977).jpg]]"
---
[Time:: 3:32]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 4]
[Album:: [[Jazz (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Stop Me Now]]
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
		intensity: page["Don't_Stop_Me_Now"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
