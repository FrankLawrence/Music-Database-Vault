---
tags: Song ⭐⭐ 
banner: "![[Free as a Bird (1987).jpg]]"
---
[Time:: 3:40]
[Artist:: [[Supertramp]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Free as a Bird (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Where I Stand]]
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
		intensity: page["Where_I_Stand"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
