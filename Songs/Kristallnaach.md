---
tags: Song  
banner: "![[Wahnsinn (1982).jpg]]"
---
[Time:: 4:59]
[Artist:: [[BAP]] ]
[Genre:: German Rock-Pop]
[Played:: 1]
[Album:: [[Wahnsinn (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Kristallnaach]]
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
		intensity: page["Kristallnaach"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
