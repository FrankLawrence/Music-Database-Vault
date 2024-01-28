---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Astro Lounge (1999).jpg]]"
---
[Time:: 3:57]
[Artist:: [[Smash Mouth]] ]
[Genre:: Pop Rock]
[Played:: 10]
[Album:: [[Astro Lounge (1999)]]]
[Year:: 1999]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[All Star]]
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
		intensity: page["All_Star"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
