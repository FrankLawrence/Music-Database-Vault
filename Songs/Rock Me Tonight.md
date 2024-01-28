---
tags: Song  
banner: "![[Jazz (1985).jpg]]"
---
[Time:: 4:36]
[Artist:: [[Freddie Jackson]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Jazz (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Rock Me Tonight]]
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
		intensity: page["Rock_Me_Tonight"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
