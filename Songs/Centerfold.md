---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Freeze-Frame (1981).jpg]]"
---
[Time:: 3:35]
[Artist:: [[J. Geils Band]] ]
[Genre:: New Wave]
[Played:: 2]
[Album:: [[Freeze-Frame (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Centerfold]]
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
		intensity: page["Centerfold"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
