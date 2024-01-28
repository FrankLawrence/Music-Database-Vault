---
tags: Song  
banner: "![[News of the World (1977).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: ]
[Album:: [[News of the World (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sheer Heart Attack]]
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
		intensity: page["Sheer_Heart_Attack"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
