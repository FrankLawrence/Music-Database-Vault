---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Songs About Jane (2004).jpg]]"
---
[Time:: 3:25]
[Artist:: [[Maroon 5]] ]
[Genre:: Pop Rock]
[Played:: 91]
[Album:: [[Songs About Jane (2004)]]]
[Year:: 2004]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This Love]]
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
		intensity: page["This_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
