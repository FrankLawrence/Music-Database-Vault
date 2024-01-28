---
tags: Song  
banner: "![[Jazz (1994).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Take 6]] ]
[Genre:: Jazz]
[Played:: 1]
[Album:: [[Jazz (1994)]]]
[Year:: 1994]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Biggest Part Of Me]]
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
		intensity: page["Biggest_Part_Of_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
