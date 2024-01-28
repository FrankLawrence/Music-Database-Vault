---
tags: Song  
banner: "![[Goodbye Yellow Brick Road (1973).jpg]]"
---
[Time:: 11:09]
[Artist:: [[Elton John]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Goodbye Yellow Brick Road (1973)]]]
[Year:: 1973]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Funeral for a friend]]
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
		intensity: page["Funeral_for_a_friend"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
