---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Music from the Edge of Heaven (1984).jpg]]"
---
[Time:: 4:27]
[Artist:: [[Wham!]] ]
[Genre:: Pop]
[Played:: 14]
[Album:: [[Music from the Edge of Heaven (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Last Christmas]]
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
		intensity: page["Last_Christmas"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
