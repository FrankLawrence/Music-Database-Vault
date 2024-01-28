---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Slash (2020).jpg]]"
---
[Time:: 3:01]
[Artist:: [[Aspyer]] ]
[Genre:: Electronic]
[Played:: 56]
[Album:: [[Slash (2020)]]]
[Year:: 2020]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Slash (Extended Mix)]]
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
		intensity: page["Slash_(Extended_Mix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
