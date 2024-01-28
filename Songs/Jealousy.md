---
tags: Song  
banner: "![[Jazz (1978).jpg]]"
---
[Time:: 3:22]
[Artist:: [[Queen]] ]
[Genre:: Soft Rock]
[Played:: 1]
[Album:: [[Jazz (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jealousy]]
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
		intensity: page["Jealousy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
