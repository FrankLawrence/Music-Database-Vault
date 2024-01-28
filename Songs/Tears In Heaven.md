---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Rush: Music from the Motion Picture Soundtrack (1992).jpg]]"
---
[Time:: 3:40]
[Artist:: [[Eric Clapton]] ]
[Genre:: Soft Rock]
[Played:: 29]
[Album:: [[Rush: Music from the Motion Picture Soundtrack (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Tears In Heaven]]
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
		intensity: page["Tears_In_Heaven"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
