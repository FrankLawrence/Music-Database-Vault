---
tags: Song  
banner: "![[News of the World (1977).jpg]]"
---
[Time:: 3:16]
[Artist:: [[Queen]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[News of the World (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sleeping On the Sidewalk]]
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
		intensity: page["Sleeping_On_the_Sidewalk"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
