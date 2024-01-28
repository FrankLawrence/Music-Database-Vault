---
tags: Song  
banner: "![[Vital Idol (1987).jpg]]"
---
[Time:: 7:04]
[Artist:: [[Billy Idol]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[Vital Idol (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Flesh For Fantasy]]
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
		intensity: page["Flesh_For_Fantasy"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
