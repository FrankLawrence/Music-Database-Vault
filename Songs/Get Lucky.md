---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Random Access Memories (2013).jpg]]"
---
[Time:: 4:09]
[Artist:: [[Daft Punk]] [[Pharrell Williams]] ]
[Genre:: Disco]
[Played:: 3]
[Album:: [[Random Access Memories (2013)]]]
[Year:: 2013]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Get Lucky]]
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
		intensity: page["Get_Lucky"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
