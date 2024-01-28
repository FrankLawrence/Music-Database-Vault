---
tags: Song  
banner: "![[Rio (1982).jpg]]"
---
[Time:: 3:25]
[Artist:: [[Duran Duran]] ]
[Genre:: New Wave]
[Played:: 2]
[Album:: [[Rio (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Hungry Like The Wolf]]
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
		intensity: page["Hungry_Like_The_Wolf"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
