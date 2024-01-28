---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Something Special (1981).jpg]]"
---
[Time:: 4:36]
[Artist:: [[Kool & The Gang]] ]
[Genre:: Funk]
[Played:: 4]
[Album:: [[Something Special (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Get Down on It]]
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
		intensity: page["Get_Down_on_It"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
