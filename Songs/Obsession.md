---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Animotion (1984).jpg]]"
---
[Time:: 3:59]
[Artist:: [[Animotion]] ]
[Genre:: New Wave]
[Played:: 2]
[Album:: [[Animotion (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Obsession]]
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
		intensity: page["Obsession"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
