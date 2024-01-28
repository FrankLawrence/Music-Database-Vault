---
tags: Song ⭐⭐⭐⭐ 
banner: "![[All The Lost Souls (2007).jpg]]"
---
[Time:: 3:37]
[Artist:: [[James Blunt]] ]
[Genre:: Pop Rock]
[Played:: 6]
[Album:: [[All The Lost Souls (2007)]]]
[Year:: 2007]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Give Me Some Love]]
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
		intensity: page["Give_Me_Some_Love"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
