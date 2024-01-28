---
tags: Song  
banner: "![[Sgt. Pepper's Lonely Hearts Club Band ().jpg]]"
---
[Time:: 2:48]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[Sgt. Pepper's Lonely Hearts Club Band ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Getting Better]]
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
		intensity: page["Getting_Better"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
