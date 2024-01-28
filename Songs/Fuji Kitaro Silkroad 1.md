---
tags: Song  
banner: "![[Fuji Kitaro Silkroad 1 (1985).jpg]]"
---
[Time:: 42:39]
[Artist:: [[Kitaro]] ]
[Genre:: ]
[Played:: 1]
[Album:: [[Fuji Kitaro Silkroad 1 (1985)]]]
[Year:: 1985]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Fuji Kitaro Silkroad 1]]
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
		intensity: page["Fuji_Kitaro_Silkroad_1"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
